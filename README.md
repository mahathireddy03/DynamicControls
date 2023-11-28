# DynamicControls
file location is ~/DynamicControls/DynamicControls/DynamicControls/XmlFile.xml.

Just add/remove the controls here.
Audio recording, per available library is having limitations where it has only one event that is “AudioInputReceived”, which will trigger when an audio file is created once recording is done. If we want to do more customization like continuous listening and high/low pich identification, we need to check with other libraries and go with custom renderers-native implementation. I have implemented with the available library which is free and compatible with my Xamarin framework (point#3).
And I faced some challenge with .Net Standard library as it was not supported with the Plugin.AudioRecorder as per my current environment for Xamarin, I need to upgrade the Mac OS and Xcode which doesn’t have access for me. So implemented with bit old version which may have some issues.
