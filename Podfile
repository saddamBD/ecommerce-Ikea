# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def testing_pods
  pod 'Quick'
  pod 'Nimble'
end

target 'ecommerce' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  pod 'InstantSearch', '~> 2.0'
  pod 'AFNetworking', '~> 3.0'
  pod 'Cosmos', '~> 16.0'
  pod 'WARangeSlider'

  # Pods for ecommerce

  target 'ecommerceTests' do
    inherit! :search_paths
    testing_pods
    # Pods for testing
  end

  target 'ecommerceUITests' do
    inherit! :search_paths
    testing_pods
    # Pods for testing
  end

end
