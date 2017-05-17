# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Bundesliga' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Bundesliga

pod 'IQKeyboardManagerSwift'

pod 'Alamofire', '~> 4.2'
pod 'AlamofireImage', '~> 3.2'
pod 'AlamofireNetworkActivityIndicator', '~> 2.0'
pod 'AlamofireObjectMapper'
pod 'SwiftyJSON', :git => 'https://github.com/SwiftyJSON/SwiftyJSON'
pod 'Moya-ObjectMapper', :git => 'https://github.com/ivanbruel/Moya-ObjectMapper'
pod 'Moya'#, :git => 'https://github.com/Moya/Moya'
pod 'ReachabilitySwift', '~> 3'
pod 'PKHUD', '~> 4.0'
pod 'Fabric'
pod 'Crashlytics'
pod 'SwifterSwift'
pod 'RealmSwift'
pod 'ObjectMapper'
pod 'ObjectMapper+Realm'
pod 'CocoaLumberjack', '2.3'
pod 'SVGKit', :git => 'https://github.com/SVGKit/SVGKit.git', :branch => '2.x'

  target 'BundesligaTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'BundesligaUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] ='3.0'
    end
  end
end
