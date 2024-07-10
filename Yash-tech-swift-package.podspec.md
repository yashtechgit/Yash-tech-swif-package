Pod::Spec.new do |s|
  s.name             = 'Yash-tech-swift-package'
  s.version          = '0.1.0'
  s.summary          = 'A demo package.'
  s.homepage         = 'https://github.com/yashtechgit/Yash-tech-swift-package.git'
  s.license          = { :type => 'MIT', :file => 'LICENSE.md' }
  s.author           = { 'Yash Tech' => 'yashtechnologies1@gmail.com' }
  s.source           = { :git => 'https://github.com/yashtechgit/Yash-tech-swift-package.git', :tag => s.version.to_s }
  s.ios.deployment_target = '13.0'
  s.swift_version = '5.0'
  s.source_files = 'Sources/MYPackage/**/*'
end
