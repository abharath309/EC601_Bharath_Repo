#EC601_Bharath_Repo

Convert speech to text...

Input is a audio file with some recording,  in this example it is test.mp3, the output is as below

This uses the SFSpeechRecognizerDelegate & SFSpeechRecognitionTaskDelegate Classes

2016-10-03 12:41:29.570055 SpeechRecognizerDemo[1346:275440] [MC] System group container for systemgroup.com.apple.configurationprofiles path is /private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles
2016-10-03 12:41:29.575341 SpeechRecognizerDemo[1346:275440] [MC] Reading from public effective user settings.
/var/containers/Bundle/Application/2DA23CA5-F103-4242-B37A-16C3732E3C93/SpeechRecognizerDemo.app/test.mp3
Optional("Hi")
Optional("Hi this")
Optional("Hi this is")
Optional("Hi this is Bharath")
Optional("Hi this is Bharath testing")
Optional("Hi this is Bharath testing the")
Optional("Hi this is Bharath testing the speech")
Optional("Hi this is Bharath testing the speech recognition")
Optional("Hi this is Bharath testing the speech recognition software")
Optional("Hi this is Bharath testing the speech recognition software")
Optional("Hi this is Bharath testing the speech recognition software")
Optional("Hi this is Bharath testing the speech recognition software")

Change the input file here.

  let filePath: String = Bundle.main.path(forResource: "test", ofType: "mp3")!
        print("\(filePath)")
        let fileURL: URL = URL(fileURLWithPath: filePath)
