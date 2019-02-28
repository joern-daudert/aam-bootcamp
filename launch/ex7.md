## Exercise 1.7 - Verify Data 

After implementing the Launch Tag on your website, you should start to see calls being sent towards AAM.

To verify if calls are being sent, open your website by going to [http://aam-bootcamp.de](http://aam-bootcamp.de) in Chrome and at the same time open the Chrome Developer Tools.

![Verify Calls](./images/devtools.png)

![Verify Calls](./images/sitedevtools.png)

Open the Chrome Developer Tools on the "Network"-view and then refresh your page.

By refreshing your page, you'll see all the calls being sent from the page to various servers, including the calls from Analytics.

![Verify Calls](./images/sitecalls.png)

To easily find the calls from Analytics, you can apply a filter by entering "b/ss" in the Filter-field.

![Verify Calls](./images/bss.png)

This should give you 1 call from AA, which is the call that sends data to AAM.

![Verify Calls](./images/url1.png)

Now it's time to check our evars that we have created before. Open the "console" tab.

![Verify Calls](./images/console.png)

In the textbox type "s.eVar1" and choose from the dropdown menue or hit tab and enter. You should see the value for eVar1 like this.

![Verify Calls](./images/console2.png)

Repeat the same for eVar2 and eVar3

![Verify Calls](./images/console3.png)

## Option B: Observe Point ## 

You can also use the Chrome Plugin "ObservePoint" [Download here](https://chrome.google.com/webstore/detail/observepoint-tagdebugger/daejfbkjipkgidckemjjafiomfeabemo?hl=de) to check your eVars directly in the Browser. 

![OP](./images/op1.png)

**Don't worry, it is preinstalled on your maschine.** 

Go the "Addons" an check whether it is enalbed or not. 

![OP](./images/op2.png)

Go to our website [http://aam-bootcamp.de](http://aam-bootcamp.de) and open developer tools 

![Verify Calls](./images/devtools.png)

Jump to the Observe point menue and refresh the page. Click on the Analytics Icon and check the eVars on the right site. 

![OP](./images/op3.png)

![OP](./images/op4.png)

**You've finished this exercise! Congratulations!**


### >>> **[Exercise 2 - Build Traits & Segments](../create_traits)** <<<

[Go Back](../README.md)
















