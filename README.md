SampleSwiftProject
==================

This is a sample iOS project without storyboard by Swift and XCdoe 6 beta 5.

1. Create Project, there is no option for empty project (without storyboard).
2. Choose Single one, and create it.
3. Delete Main.storyboard file.
4. Select info.plist and delete "Main Storyboard file base name".
5. Add some code in AppDelegate.m (funciton "application didFinishLaunchingWithOptions") makes it looks like below

  func application(application: UIApplication!, didFinishLaunchingWithOptions launchOptions: NSDictionary!) -> Bool {
  
        self.window = UIWindow(frame: UIScreen.mainScreen().bounds)
        // Override point for customization after application launch.
        self.window!.backgroundColor = UIColor.whiteColor()
        self.window!.makeKeyAndVisible()
        
        return true
  }
  
6. Add your viewcontroller as you know in Objective C.
7. Run and enjoy it.
