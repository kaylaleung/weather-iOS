# Weather

Starter project for the Clima app https://www.appbrewery.co/p/how-to-make-app-ios Copyright © The App Brewery

## Finished App
![Finished App](https://github.com/londonappbrewery/Images/blob/master/Clima.gif)


## Fix for App Transport Security Override

```XML
	<key>NSAppTransportSecurity</key>
	<dict>
		<key>NSExceptionDomains</key>
		<dict>
			<key>openweathermap.org</key>
			<dict>
				<key>NSIncludesSubdomains</key>
				<true/>
				<key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
				<true/>
			</dict>
		</dict>
	</dict>
```



