def import_pods
  pod 'Alamofire', '~> 4.7'
  pod 'Alamofire-Synchronous', '~> 4.0'
  pod "PromiseKit", 
  pod 'BigInt', 
  pod 'CryptoSwift', 
  pod 'Result', 
  pod 'libsodium', 
  pod 'secp256k1_ios',
end

target 'web3swift-macOS' do
  platform :osx, '10.13'
#  use_frameworks!
  use_modular_headers!
  import_pods
  
  target 'web3swift-macOS_Tests' do
    inherit! :search_paths
  end
end

target 'web3swift-iOS' do
  platform :ios, '9.0'
#  use_frameworks!
  use_modular_headers! 
  import_pods
  
  target 'web3swift-iOS_Tests' do
    inherit! :search_paths
  end
end
