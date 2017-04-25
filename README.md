# ImageTextField

A Designable Textfield For adding textfield leftview and rightview images in storyboard for swift 3.0 .

Using ImageTextField you can set left and right imageview in storyboard with padding. At a single time image is either show on left side or right side. Also you can add Layer to TextField. If you add any color to Bottom Color it will add a layer in 
bottom layer and it's borderStyle will change. if you set it clear color it will change to  .roundedRect borderStyle.

<img src = "https://cloud.githubusercontent.com/assets/7422405/23651176/b1db6c48-034a-11e7-90c0-571da6a150f3.png" />


# NOTE
if you want to add image on right side you have to select the Force Right-to-Left option in semantic in interface builder.
<img src = "https://cloud.githubusercontent.com/assets/7422405/23246591/dd38df2c-f9ba-11e6-9c6c-aa0171926d62.png"/>

# Installation

Manually

Clone or Download this Repo. Then simply drag the class ImageTextField.swift to your Xcode project.
 
# CocoaPods

CocoaPods is a dependency manager for Cocoa projects. You can install it with the following command:

$ gem install cocoapods
To integrate TableViewReloadAnimation into your Xcode project using CocoaPods, specify it in your Podfile:

    source 'https://github.com/CocoaPods/Specs.git'
    platform :ios, '9.0'
    use_frameworks!

    target '<Your Target Name>' do
      pod 'ImageTextField','~> 1.0.0'
    end

Then, run the following command:

$ pod install

# Requirements

Swift 3.0

iOS 8.0 or later


# Contributions

Any contribution is more than welcome! You can contribute through pull requests and issues on GitHub.

