# YouDecide
I use Virtual tourist app but I add one Feature like login/sign up feature in the begining of the app.
Compatible for Xcode 9.3 and above
It allows user to login/signup to udacity, then can view a map for all over the world and can press and hold on any city to view a collection of flicker images. And finally the user can delete or refresh any images collection.



# Installation
First you have to install the podfile with terminal/command line
In order to use it you will need to create a `Podfile` if you do not already have one. Information on installing cocoapods and creating a Podfile can be found at [Cocoapods.org](http://cocoapods.org/). (Hint — to install cocoapods, run `sudo gem install cocoapods` from the command line; to create a Podfile, run `pod init`).

Open up the Podfile and add the following dependency:

# platform :ios, '9.0'

target 'virtualTourist' do
    pod 'Alamofire'
    pod 'Kingfisher'
    
end

Save your Podfile and run 'pod install' from the command line.


# Run the App
Finally, now you open the ‘virtualTourist’ workspace then press run and have fun :)




