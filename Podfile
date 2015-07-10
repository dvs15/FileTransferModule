source 'https://github.com/CocoaPods/Specs.git'
source 'ssh://git@git.ait.local/front-end/podspecs-ios.git'

platform :ios, '7.1'
inhibit_all_warnings!

def import_pods
    pod 'AllJoynLibsiOS', :git => 'git@git.ait.local:front-end/alljoyn-libs-ios.git', :commit => '9b6863e623e2709ae2a5eb6f3d5ad747df1742d2' #'~> 0.1'
end

xcodeproj 'FileTransferModule'

target :FileTransferModule do
    import_pods
end

target :FileTransferModuleTests do
    import_pods
end