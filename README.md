# wwc-sv-week5
<b><center>Learn Firebase</center></b>

Create real time chat using Firebase
Cocoapods used: Firebase, JSQMessagesViewController

Flow of Steps:

<li>Starter project contains a simple dummy login screen <a href="https://drive.google.com/open?id=0B8clxQt2zUqKdTBHR1pkWGNHR1U"> Download here</a><li>
<li>Create an empty pod file (pod init) and add pod 'Firebase' pod 'JSQMessagesViewController'<li>
<li>pod install and open the workspace file </li>
<li> run </li>
<li> <b> Create a Firebase account <a href="https://www.firebase.com/signup"> Here </a></b></li>
<li>Enable anonymous authentication</li>
<li> Inside LoginViewController.swift import Firebase </li>
<div>class LoginViewController: UIViewController {
 
  // MARK: Properties
  var ref: Firebase! // 1
 
  override func viewDidLoad() {
    super.viewDidLoad()
    ref = Firebase(url: "https://<my-firebase-app>.firebaseio.com") // 2
  }
}</div>


