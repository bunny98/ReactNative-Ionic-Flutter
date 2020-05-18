## Comparing React Native, Ionic and Flutter

|Metric| React Native  |     Ionic     |     Flutter     |
|------| ------------- | ------------- |-----------------|
| **Developed By** | Facebook | Drifty Co.  | Google  |
| **Used in**  | [Instagram](https://www.instagram.com/), [Facebook](https://www.facebook.com/), [UberEats](https://www.ubereats.com/) |  [MarketWatch](https://www.marketwatch.com/), [Pacifica](https://www.pacificacompanies.co.in/),[Sworkit](https://sworkit.com/)  | [Alibaba](https://www.alibaba.com/?src=sem_ggl&cmpgn=8652583628&adgrp=88567885882&fditm=&tgt=kwd-14739453&locintrst=&locphyscl=9040199&mtchtyp=e&ntwrk=g&device=c&dvcmdl=&creative=406886227602&plcmnt=&plcmntcat=&p1=&p2=&aceid=&position=&gclid=CjwKCAjwwYP2BRBGEiwAkoBpAre5FTQpdiA5E2bTIXZYY3BhUuGaht4Fta1rMnaHEY7y6gWTIQ_uFRoCmcAQAvD_BwE), [Birch Finance](https://birchfinance.com/), [Reflectly](https://reflectly.app/) |
| **Programming language** |  React library and JavaScript  | HTML, CSS, JavaScript and [Cordova Plugin](https://github.com/ionic-team/cordova-plugin-ionic)  | [Dart](https://dart.dev/)  |
| **Community Support**  | Strong Community Support with numerous active users helping eachother  | Since it was built on AngularJS almost 7 years ago, its backed by a strong community as well |  Relatively new, so as compared to the other two, has a weaker community support |
| **Performance (from Runtime Perspective)**| React Native lets you build an application that provides native look-and-feel by invoking native APIs and components through a JS Bridge. Whenever the user interacts with the application or the application changes its state on it own, which can be as frequent as 60 times a second, the application has to communicate to the platform rendering the application through a bridge. This gives rise to performance implications. <img src="Pictures/RN.png"> |    Ionic is different than other frameworks as it uses web technologies like HTML, CSS, and JavaScript to create hybrid cross-platform apps. It needs plugins and third-party packages to wrap your application in native cover so its slower than React Native. It creates web views of your application and displays them in your platform and communicates to services like cameras and geolocation through a bridge.<br> <img src="Pictures/Ionic.png"> |  Flutter goes a step ahead because there is no native transition or some bridges to connect with the native environment. Flutter eliminates the bridge or any context switch needed to go from your app to a specific platform and moves the rendering in your application! All it requires of the platform is a canvas to render the widgets so that they can appear on the device screen and access to events like fingertaps and services like bluetooth, camera, etc. <img src="Pictures/Flutter.png"> |
| **Popularity**  | React Native is more popular than the other two as many tech giants are using it in their production environment including Facebook, Instagram, Pinterest, Skype, Tesla, Uber, Walmart, Salesforce, Vogue | Ionic is very popular among web and mobile app developers due to its easy learning curve. It is used by MarketWatch, Pacifica, Sworkit, Nationwide, and many more | Flutter has just entered the market but grown in popularity in very less time. It is used by Alibaba, Hamilton Musical, Greentea, Google Ads  | 
| **Supported Platforms** | Android, iOS, UMP | iOS, Android, Web  | Android, iOS, Google Fuchsia  |
| **Open Source** | Yes | Yes, paid too! | Yes |
| **Front-end Support** | Native Components & Declarative UI  | HTML, CSS, wide range of UI Designs | Great support for attractive UIs and built-in Widgets |
| **Code Reusabilty** | Once coded components can be re-used wherever in the application.   | Awesome re-usability! The “wrapped web app” concept ensures that you can easily re-use your code — you’re just building a wrapped web app in the end.  | Reusable Widgets which are displayed in the application just the way you code them, i.e., they don't adapt to the underlying platform. |
|**Documentation**| Up-to-date but imprecise  |   Up-to-date but long drawn | Precise, Clear, up-to-date  |
| **Learning Curve**  | Steep Learning Curve |  Easy Learning Curve due to web technologies like Angular and TypeScript | Moderate Learning Curve |
|**Time-to-Market of App**| Slower as compared to the other two | Faster than React, Slower than Flutter | Fastest among the three |
|**Code Testing**|  Needs a real mobile device or emulator to test the code | Using any browser, the code can be tested | Needs a real mobile device or emulator to test the code   |
|**Error Reporting**| Really messy! | Compact and readable  | Compact and readable  |
| **Native Performances**  |  Good  | Worst | Best  | 

### To Summarize

**Choose Flutter when you want cross-platform, highly-attractive UI, excellent native performance, quicker time-to-market, and competitive advantage of using Dart in your programming environment.<br>
Choose React Native when you want to leverage the support from the stronger and mature community, native app performance, and popular JavaScript in developing cross-platform apps<br>
If you are low on budget and want excellent performance, you can opt for Ionic**


