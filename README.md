# iOS Base Project

The idea of this project is to serve as a template when starting a new project. It will contain 3 build configurations: **Debug**, **AdHoc** and **Release**. We'll integrate CocoaPods using Fabric for distributing the app, and then we'll use [FBTweaks](https://github.com/facebook/Tweaks), and awesome library from facebook.

We'll start by creating an App ID. In Member Center

![Member Center](https://cloud.githubusercontent.com/assets/3428186/12683995/725ca4d4-c69b-11e5-9033-2f118ab73b57.png?raw=true "Member Center")	

Go to **Certificates, Identifiers & Profiles**:

![Certificates, Identifiers & Profiles](https://cloud.githubusercontent.com/assets/3428186/12683996/727ba29e-c69b-11e5-9b25-8103dfe77a92.png?raw=true "Certificates, Identifiers & Profiles")	

And then to **Identifiers** inside iOS Apps section:

![Identifiers](https://cloud.githubusercontent.com/assets/3428186/12684000/72925e9e-c69b-11e5-8700-e1af1f46ba19.png?raw=true "Identifiers")	

Then click on the **Plus (+)** sign on the right of the screen, 

![App ID Description](https://cloud.githubusercontent.com/assets/3428186/12683999/7290b95e-c69b-11e5-95f5-d2f55664fb8d.png?raw=true "App ID Description")	

And enter an App ID Description. Use a properly description for your App ID. You can change it later though. Then, enter an App ID Suffix:

![App ID Suffix](https://cloud.githubusercontent.com/assets/3428186/12683997/728dedc8-c69b-11e5-92aa-b3e0956b2ece.png?raw=true "App ID Suffix")	

This one would be permanent, so **think it well**, because you can't change it later.

![App ID Confirmation](https://cloud.githubusercontent.com/assets/3428186/12683998/728e7d1a-c69b-11e5-91c2-b767792ad78a.png?raw=true "App ID Confirmation")

Then, once all the capabilities have been selected, click on **Submit**.

Now we'll create three provisioning profiles: one for **Development**, another for **AdHoc** distribution of our app (like distributing the app internally with the QA team and to our client for weekly builds), and the last one for **Release**.

![Provisioning Profiles section](https://cloud.githubusercontent.com/assets/3428186/12684001/729404ec-c69b-11e5-9d98-9ffe3a4dd05b.png?raw=true "Provisioning Profiles section")


Go to the **Provisioning Profiles** section, and then click on the **Plus (+)** sign.

![Development Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684002/729bf3dc-c69b-11e5-9458-740985086b80.png?raw=true "Development Provisioning Profile")

Then, select **iOS App Development** option and click **Continue**.

![App ID for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684003/72aa9144-c69b-11e5-9aa9-0943f3de6499.png?raw=true "App ID for Provisioning Profile")

Then, select the previously created App ID and click **Continue**.

![Certificates for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684004/72afd0f0-c69b-11e5-9dfb-b3a9123e109f.png?raw=true "Certificates for Provisioning Profile")

Then, select the certificates you want to include in the Provisioning Profile and click **Continue**.

![Devices for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684005/72b14034-c69b-11e5-8c28-690744656342.png?raw=true "Devices for Provisioning Profile")

Then, select the devices you want to include in the Provisioning Profile and click **Continue**.

![Name for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684006/72b1daa8-c69b-11e5-9729-925799175a70.png?raw=true "Name for Provisioning Profile")

Finally, pick a name for the Provisioning Profile and click **Generate**.

We are going to do the same for the **AdHoc** and the **Release** provisioning profiles.

![Provisioning Profiles section](https://cloud.githubusercontent.com/assets/3428186/12684007/72b3a27a-c69b-11e5-8d60-33daae1ff6f2.png?raw=true "Provisioning Profiles section")

Click again on the **Plus (+)** sign.

![AdHoc Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684008/72bd7f2a-c69b-11e5-922c-4ad9c6aa228d.png?raw=true "AdHoc Provisioning Profile")

Now select the **Ad Hoc** option and click **Continue**.

![App ID for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684009/72c6bbe4-c69b-11e5-9bc5-af96d31d65e5.png?raw=true "App ID for Provisioning Profile")

Again, select the previously created App ID and click **Continue**.

![Certificates for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684011/72cfaac4-c69b-11e5-8806-d1052d464f3d.png?raw=true "Certificates for Provisioning Profile")

Now select a valid **Distribution** certificate and click **Continue**.

![Devices for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684010/72ceb7f4-c69b-11e5-9981-e0fc3883689a.png?raw=true "Devices for Provisioning Profile")

Then, select the devices you want to include in the Provisioning Profile and click **Continue**.

![Name for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684012/72d1811e-c69b-11e5-88a2-cd414bfcad61.png?raw=true "Name for Provisioning Profile")

Finally, pick a name for the Provisioning Profile and click **Generate**.

The last Provisioning Profile that we are going to create will be the **Release** Provisioning Profile.

![Provisioning Profiles section](https://cloud.githubusercontent.com/assets/3428186/12684013/72d272f4-c69b-11e5-98a2-201f06e0beab.png?raw=true "Provisioning Profiles section")

![Release Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684014/72e07f0c-c69b-11e5-83a0-0ed0764d4050.png?raw=true "Release Provisioning Profile")

![App ID for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684015/72e68f50-c69b-11e5-81e9-029154e31c9a.png?raw=true "App ID for Provisioning Profile")

![Certificates for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684017/72ee678e-c69b-11e5-911f-e97186c90556.png?raw=true "Certificates for Provisioning Profile")

![Name for Provisioning Profile](https://cloud.githubusercontent.com/assets/3428186/12684018/72ef1c10-c69b-11e5-9c24-d9c50ffc6612.png?raw=true "Name for Provisioning Profile")

You'll notice that for this profile we didn't have to choose the devices we want to include. That's because this profile is used to sign the App and release it to the AppStore, so in that way it can be installed in every single iOS Device.



![iTunes Connect Home Page](https://cloud.githubusercontent.com/assets/3428186/12684016/72ee7738-c69b-11e5-8121-a9633d8e1a10.png?raw=true "iTunes Connect Home Page")

Once all the Provisioning Profiles had been generated, we'll go to the **iTunes Connect** home page and login. 

![My Apps Section](https://cloud.githubusercontent.com/assets/3428186/12684019/72f328b4-c69b-11e5-9557-32fcdc184c05.png?raw=true "My Apps Section")

Then, access to My Apps section and click on the **Plus (+)** sign and select the **New App** option.

![New App](https://cloud.githubusercontent.com/assets/3428186/12684020/73007fc8-c69b-11e5-9139-780cd091201e.png?raw=true "New App")

Fill the App details, selecting the Bundle ID with the App ID previously created. The **SKU** is a product identifier of your organization, it can be anything. Then click **Create**.


![XCode](https://cloud.githubusercontent.com/assets/3428186/12684021/73042e48-c69b-11e5-8f57-6691e4a50582.png?raw=true "XCode")

Then, open the XCode and click on **Create a new XCode project**. 

![Single View Application](https://cloud.githubusercontent.com/assets/3428186/12684023/730cf0c8-c69b-11e5-8d8b-38cbfb19a8b2.png?raw=true "Single View Application")

And select the template of your choice and click **Next**.

![Project details](https://cloud.githubusercontent.com/assets/3428186/12684024/730dab12-c69b-11e5-854c-46b99263f2c8.png?raw=true "Project details")

Then fill your company details and click **Next** and in the next screen select the project destination and click **Create**.

![CocoaPods](https://cloud.githubusercontent.com/assets/3428186/12684022/730b97b4-c69b-11e5-809c-b2e660fa2e6d.png?raw=true "CocoaPods")

Then we will close the XCode and open a terminal and enter `pod install`. Previously, create a `Podfile` and include the dependencies you want for the project. I've installed `Tweaks`, among others, which we'll include it later in our project.

![CocoaPods project structure](https://cloud.githubusercontent.com/assets/3428186/12684025/7312aacc-c69b-11e5-9de0-9866fb583e41.png?raw=true "CocoaPods project structure")

At this moment, our project should look similar to this.

![Accounts section](https://cloud.githubusercontent.com/assets/3428186/12684026/7320645a-c69b-11e5-9352-821bac0577dc.png?raw=true "Accounts section")

Then we will have to go to **XCode** -> **Preferences** and enter the **Accounts Section**. Then click on **View Details...** and 

![Download Provisionings](https://cloud.githubusercontent.com/assets/3428186/12684027/732a2fe4-c69b-11e5-9509-2dab6d7b8a85.png?raw=true "Download Provisionings")

Click on **Download All**. This will download all of our certificates. We will need them to configure our build settings.

![Project settings](https://cloud.githubusercontent.com/assets/3428186/12684030/732ece3c-c69b-11e5-86af-16cb37de21b4.png?raw=true "Project settings")

Go to the project settings

![Duplicate Release setting](https://cloud.githubusercontent.com/assets/3428186/12684028/732b1b48-c69b-11e5-8981-32243a2ccdd6.png?raw=true "Duplicate Release setting")

And click the **Plus (+)** sign in the **Configurations** section, and select **Duplicate "Release" Configuration**, and name it **AdHoc** or the one of your choice. That will be the configuration we will use to distribute internally our app.

![Default code signing settings](https://cloud.githubusercontent.com/assets/3428186/12684031/73354eba-c69b-11e5-9f03-3809b3ec74be.png?raw=true "Default code signing settings")

Then, select the Target settings, and check that the **Code Signing** section looks like the picture from above, we will change that

![Custom code signing settings](https://cloud.githubusercontent.com/assets/3428186/12684053/73abd3e6-c69b-11e5-8f92-af0e158a97a6.png?raw=true "Custom code signing settings")

For this ones. Check that in the the **Debug** Provisioning Profile has the **Automatic** option selected, whereas the **AdHoc** and the **Release** Provisioning Profiles have a the ones created before. This is because if we select **Automatic** for both ones, XCode will use the last one generated, and we don't want that. Also check that in the **Code Signing Identity** section we are using the same **Distribution Certificate** for both **AdHoc** and **Release**, and in **Debug** we are not code signing the app.

![Preprocessing](https://cloud.githubusercontent.com/assets/3428186/12684032/733dcb3a-c69b-11e5-817a-f20345e52ba9.png?raw=true "Preprocessing")

Then, in the **Preprocessing** section, we will add a **RELEASE=1** macro in the **Release** configuration, and the same for the **AdHoc** configuration. With this macros, we can distinguish then if we have to create the **Tweaks** window or not. 

![App Delegate](https://cloud.githubusercontent.com/assets/3428186/12684034/734ac362-c69b-11e5-84fc-29fa1b4949cd.png?raw=true "App Delegate")

Then, in the App Delegate, we will import this 

`#import "FBTweakShakeWindow.h"`

and in the `- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions` method, and add the following code: 

```c
    CGRect screenBounds = [[UIScreen mainScreen] bounds];
#ifndef RELEASE
    self.window = [[FBTweakShakeWindow alloc] initWithFrame:screenBounds];
#else
    self.window = [[UIWindow alloc] initWithFrame:screenBounds];
#endif
    self.window.backgroundColor = [UIColor whiteColor];
    
    UIViewController *rootVC = [UIViewController new];
    rootVC.view.backgroundColor = [UIColor redColor];
    
    UINavigationController *navVC = [[UINavigationController alloc] initWithRootViewController:rootVC];
    
    self.window.rootViewController = navVC;
    
    [self.window makeKeyAndVisible];
    
    [Fabric with:@[[Crashlytics class]]];
    
    return YES;
```


This code will check if we are not in the **RELEASE** build, and if that's the case, will create an `FBTweakShakeWindow`, for debugging purposes, being able to add tweaks to our project, like changing the API URL, or another useful stuff.

![Fabric](https://cloud.githubusercontent.com/assets/3428186/12684033/7349f64e-c69b-11e5-9cdf-11daaf904ec6.png?raw=true "Fabric")

Now we'll add Fabric for distributing internally our app or to our clients. First of all download it from [here](http://fabric.io), and create an account or login into yours. Then, open it and click on **+ New App**.

![Select Project](https://cloud.githubusercontent.com/assets/3428186/12684035/734c306c-c69b-11e5-8fb6-f6ace781c377.png?raw=true "Select Project")

Then, select your project and click **Next**.

![Select Organization](https://cloud.githubusercontent.com/assets/3428186/12684036/734deeb6-c69b-11e5-9309-f51b52e266f5.png?raw=true "Select Organization")

Then, select your organization and click **Next**.

![Select Kit](https://cloud.githubusercontent.com/assets/3428186/12684037/7356fb8c-c69b-11e5-91a0-e02d3346276a.png?raw=true "Select Kit")

Then, select a Kit to install and click **Next**. In this case we will install **Crashlytics**.

![Agreeee](https://cloud.githubusercontent.com/assets/3428186/12684038/735eeba8-c69b-11e5-97f4-1470118af216.png?raw=true "Agreeee")

Agree to this

![Install via CocoaPods](https://cloud.githubusercontent.com/assets/3428186/12684040/73696f38-c69b-11e5-9498-b2a956b00773.png?raw=true "Install via CocoaPods")

Select **Install via CocoaPods** and follow the instructions:

![Step 1](https://cloud.githubusercontent.com/assets/3428186/12684039/7367b08a-c69b-11e5-9e9f-efa3a3ef3550.png?raw=true "Step 1")

![Step 2](https://cloud.githubusercontent.com/assets/3428186/12686856/033674ee-c6ab-11e5-8d2e-583b83aecd12.png?raw=true "Step 2")

![Step 3](https://cloud.githubusercontent.com/assets/3428186/12684044/737be5a0-c69b-11e5-9e1e-ed9813f2bde7.png?raw=true "Step 3")

![Step 4](https://cloud.githubusercontent.com/assets/3428186/12684046/7384f9b0-c69b-11e5-9862-c6bf01b881bb.png?raw=true "Step 4")

![Step 5](https://cloud.githubusercontent.com/assets/3428186/12684047/738b27f4-c69b-11e5-8d3c-0a120388d025.png?raw=true "Step 5")

![Step 6](https://cloud.githubusercontent.com/assets/3428186/12684048/738c5f70-c69b-11e5-915d-dafa9c868fba.png?raw=true "Step 6")

Then, go back to the XCode and click on **Edit Scheme**, and in the **Archive** section, change the **Build Configuration** and select **AdHoc**. We will have to change back to **Release** if we want to make a release build.

Then, click on **Product** -> **Archive** and wait until the archive it's done (hopefully, if the XCode doesn't complains with the Provisioning Profiles).

![Fabric archive](https://cloud.githubusercontent.com/assets/3428186/12684052/73a87eb2-c69b-11e5-9f89-4da5fb8263f9.png?raw=true "Fabric archive")

Fabric will popup a notification asking us if we want to distribute the recently generated archive. Click on **Distribute** and then 

![Fabric emails](https://cloud.githubusercontent.com/assets/3428186/12684054/73ac3c64-c69b-11e5-9b8a-5f3c30b9f707.png?raw=true "Fabric emails")

Enter the emails of the testers you want to test the app. Enter the release notes and click **Next** and wait until the archive is uploaded.

![Fabrice archive uploaded](https://cloud.githubusercontent.com/assets/3428186/12684056/73c4932c-c69b-11e5-88d2-d72618719268.png?raw=true "Fabrice archive uploaded")

![Fabric email](https://cloud.githubusercontent.com/assets/3428186/12684060/73c9b276-c69b-11e5-9635-77789b2c6974.PNG?raw=true "Fabric email")

We will receive a Fabric invitation to test our app. Click on **Let Me In** and accept the message (you'll have to open in **Safari** browser).

![Fabric install](https://cloud.githubusercontent.com/assets/3428186/12684058/73c8a96c-c69b-11e5-8188-6089bd75e590.PNG?raw=true "Fabric install")

Finally, click on **Install** and accept the popup

![Fabric install popup](https://cloud.githubusercontent.com/assets/3428186/12684059/73c8ba56-c69b-11e5-92c1-b02e4b671fce.PNG?raw=true "Fabric install popup")


And that's all. You've learned how to create an iOS App from scratch, create the required Provisioning Profiles to develop and distribute your app, and then how to distribute via **Fabric**.


Hope you enjoyed this tutorial, and good bye!




![Drop mic](https://imgflip.com/readImage?iid=40516894?raw=true "Drop mic")