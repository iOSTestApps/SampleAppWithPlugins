# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'SampleAppWithPlugins' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SampleAppWithPlugins
    pod 'Alamofire', '~> 4.7'

      pod 'Kingfisher', '~> 4.10'


end

plugin 'cocoapods-keys', {
  :project => "Eidolon",
  :keys => [
    "HockeyProductionSecret",
    "HockeyBetaSecret",
    "MixpanelProductionAPIClientKey",
  ]}
