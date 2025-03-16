# EasyOSS Project sample for UE 5.4.4, EOS OSS

## Requirements

1. **You must run the project with Unreal engine version 5.4.4** 
2. **You must have a product configured in epic game dev portal**
3. **You must configure `EOS Auth Dev Tool`**

## How to run the sample

1. Go to `config/DefaultEngine.ini`, then configure EOS Voice Chat according to your EOS Product configuration
2. Open the .uproject file with UE Editor Version 5.4.4
3. Go to `Edit->Plugins`, then make sure that Easy OSS Plugin is activated. You must have the plugin installed for this engine first.
4. Go to `Edit->Project Settings`, search for epic online services plugin then configure it according to you EOS Product configuration
5. To test with auth dev tool, add your creds in the tool then modify bat scripts to fit your added accounts.
6. To test without Auth Dev Tool, go to MainMenu/Levels/Startup/Widgets/WB_Login, then replace Auto Login Task with Login by providing `accountportal` as auth type.
