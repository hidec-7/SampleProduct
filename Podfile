# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'sampleProduct' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for sampleProduct

  target 'sampleProductTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'sampleProductUITests' do
    # Pods for testing
  end  

end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '12.0'
    end
  end
end
