# Reference_deck


https://developer.apple.com/videos/play/wwdc2014/216/
https://developer.apple.com/videos/play/wwdc2014/214/

https://github.com/John-Lluch/SWRevealViewController/archive/master.zip


https://www.raywenderlich.com/78568/create-slide-out-navigation-panel-swift

https://www.dropbox.com/s/6n09lrr15ibcsl4/SidebarMenuStart.zip?dl=0

https://developer.apple.com/videos/play/wwdc2016/402/


https://itunes.apple.com/ru/course/razrabotka-ios-prilozenij/id941293188?l=en




  if let jsonResult = try NSJSONSerialization.JSONObjectWithData(data!, options: []) as? NSDictionary {
                print("ASynchronous\(jsonResult)")





            // Print out response string
            let responseString = NSString(data: data!, encoding: NSUTF8StringEncoding)
            print("responseString = \(responseString)")
            
            
            // Convert server json response to NSDictionary
            do {
                if let convertedJsonIntoDict = try NSJSONSerialization.JSONObjectWithData(data!, options: []) as? NSDictionary {
                    
                    // Print out dictionary
                    print(convertedJsonIntoDict)
                    
                    // Get value by key
                    let firstNameValue = convertedJsonIntoDict["userName"] as? String
                    print(firstNameValue!)
                    
                }
            } catch let error as NSError {
                print(error.localizedDescription)
            }
            
        }



https://www.dropbox.com/s/6n09lrr15ibcsl4/SidebarMenuStart.zip?dl=0
