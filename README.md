# Ex-6-GAE
# Date:
# Aim:
ToinstallGoogleAppEngine.Createhelloworldappandothersimplewebapplicationsusingpython/java

GoogleCloudPlatform(GCP)

GoogleCloudPlatform(GCP),offeredbyGoogle,isasuiteofcloud computingservicesthatrunsonthesameinfrastructurethatGoogleuses internally for its end-user products, such as Google Search,Gmail,filestorage, andYouTube.
	Alongsideasetofmanagementtools,itprovidesaseriesofmodularcloudservicesincludingcomputing,datastorage,dataanalyticsandmachinelearning.
GoogleCloudPlatformprovidesinfrastructureasaservice,platformasaservice,andserverlesscomputingenvironments.

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/037c6ed1-b47d-482a-8c3e-119638be16a0)


Platform asaService(PaaS)
Cloudcomputingservicewhichprovidesacomputingplatformandasolutionstack asaservice.
Consumercreatesthesoftwareusingtoolsand/or libraries fromtheprovider.
Providerprovidesthenetworks,servers,storage,etc.



GoogleAppEngine:

GoogleAppEnginewasfirstreleasedasabetaversioninApril2008.

It isaisa PlatformasaService(PaaS)cloudcomputingplatformfordevelopingandhostingwebapplicationsinGoogle-manageddatacenters.
Google‘sAppEngineopensGoogle‘sproductiontoanypersonintheworldatno
charge.
GoogleAppEngineissoftwarethat facilitatestheusertorunhiswebapplicationsonGoogleinfrastructure.
Itismorereliablebecausefailureofanyserver willnotaffecteithertheperformanceoftheenduserortheserviceoftheGoogle.
Itvirtualizesapplicationsacross multipleserversanddatacenters.
Othercloud-basedplatformsincludeofferingssuchas Amazon Web

ServicesandMicrosoft's AzureServices Platform.

IntroductionofGoogleAppEngine
GoogleAppEngineletsyourunyourwebapplicationsonGoogle'sinfrastructure. App Engine applications are easy to build, easy to maintain,andeasytoscaleasyourtrafficanddatastorageneedsgrow.WithAppEngine,there are no servers to maintain :You just upload your application, and it'sreadytoserveyourusers.
You   can   serve  your    app    from   your    own   domain    name    (suchas https://www.example.com/) using Google Apps. Or, you can serve yourapp using a free name on the appspot.com domain. You can share yourapplicationwiththeworld, orlimitaccesstomembersofyour organization.
GoogleAppEnginesupportsappswritteninseveral programminglanguages.
With AppEngine'sJavaruntimeenvironment,youcan buildyourappusingstandardJavatechnologies,includingtheJVM,Javaservlets,andtheJavaprogramming	language—oranyotherlanguageusingaJVM-basedinterpreterorcompiler,suchasJavaScriptorRuby. AppEnginealsofeaturesadedicatedPythonruntimeenvironment,whichincludesafastPythoninterpreter		and	thePythonstandardlibrary.TheJavaandPythonruntimeenvironmentsarebuilttoensurethatyourapplicationrunsquickly,securely,andwithoutinterferencefromotherappsonthesystem.
With AppEngine, you only pay for what you use. There are no set-up costsand no recurring fees. The resources your application uses, such as storageandbandwidth,aremeasuredbythegigabyte,andbilledatcompetitiverates.You control the maximum amounts of resources your app can consume, so italwaysstayswithinyourbudget.App Enginecostsnothingto getstarted. Allapplicationscanuseupto500MBofstorageandenoughCPUandbandwidth
to support an efficient app serving around 5million page views amonth,absolutelyfree.Whenyouenablebillingforyourapplication,yourfreelimits are raised, and you only pay for resources you use above the freelevels.
Architecture ofGoogleAppEngine

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/7528cfb5-e628-473e-a8a6-03d45484d109)


FeaturesofGoogleAppEngine


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/74df22dc-a1ec-4680-a9b0-ee7cc79085bd)


GAEApplicationEnvironment:


Google App Engine makesit easy tobuild an application that runs reliably,even under heavy load and with large amounts of data. App Engine includes thefollowingfeatures:
Persistentstoragewithqueries, sortingandtransactions Automaticscalingandloadbalancing
APIsforauthenticatingusersandsendingemailusingGoogleAccounts Taskqueuesforperforming workoutsideofthescopeofawebrequest
Scheduledtasksfortriggering eventsatspecifiedtimesandregularintervals

Dynamicwebserving,withfullsupport forcommonwebtechnologies

JavaRuntimeEnvironment


You can develop your application for the Java runtime environment usingcommon Java web development tools and API standards. Your app interactswith the environment using the Java Servlets standard, and can use commonwebapplication technologiessuchasJavaServerPages
TheJavaruntimeenvironmentusesJava6.TheAppEngineJavaSDKsupports developing apps using either Java5 or 6.The environment includestheJavaSERuntimeEnvironment(JRE)6platformandlibraries.TherestrictionsofthesandboxenvironmentareimplementedintheJVM.Anappcan use any JVM byte code or library feature, as long as it does not exceedthesandboxrestrictions.Forinstance,bytecodethatattemptstoopenasocketorwritetoafilewillthrow aruntimeexception.
YourappaccessesmostAppEngineservicesusingJavastandardAPIs.Forthe AppEngine data store, the Java SDK includes implementations of the JavaDataObjects(JDO)andJavaPersistenceAPI(JPA)interfaces.Yourappcanuse the JavaMailAPItosend emailmessageswiththeAppEngineMailservice.Thejava.netHTTPAPIsaccessestheAppEngineURLfetchservice.  AppEnginealsoincludeslow-levelAPIsforitsservicestoimplementadditionaladapters,ortousedirectlyfromtheapplication.Seethedocumentationforthedatastore,memcache,URLfetch,mail,imagesandGoogleAccountsAPIs.Typically,JavadevelopersusetheJava
programming
languageandAPIstoimplementwebapplicationsfortheJVM. WiththeuseofJVM-compatiblecompilersorinterpreters,youcanalso useotherlanguagestodevelopwebapplications,suchas JavaScript,Ruby.


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/5a6b37a0-8ddd-4e28-8769-09a5011c5ec0)





WorkflowofGoogleAppEngine


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/455ab397-4001-4e65-b206-9690ae1cac1d)


Step1:Logintowww.cloud.google.com

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/1d562ec9-a9e3-4b67-8224-79e14aafffd3)


Step2:GotoConsole

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/44080c1d-2b2d-4bbb-a2a6-2d20d0da1609)


Step3:GoogleCloudPlatformisshown

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/841f00a4-ce9b-4b1d-bfe5-2ce2961562d2)


Step4:ClickDashboardintheGoogleCloudPlaform

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/241b1228-1c2d-4927-bb8d-bdec4ad9eb57)


Step5:DashboardintheGoogleCloudPlaform

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/187fafc8-95de-4a1e-8a57-6528e3467c13)


Step6:ClickNewProjectandgiveuniqueProjectName.


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/2b526fab-c4f6-4ae3-9a73-d4218f80a9ec)


Example:kcet-cloud-project


Step7:GoogleAppEngineisinitated

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/5c2e939f-5b50-497c-ac4a-263561e7c7df)


Step8: ClickcreateApplication

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/f9111343-35f6-43af-8f68-3fbef652d29b)


Step9:CreateappandSelectLanguagePython

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/61c0f158-6d3f-49fe-a336-f9de09368630)


Step10: PythonappiscreatedinGoogleAppEngine
![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/00185cbc-03ea-433d-a263-56980040f761)


Step11 :PythonappEngineapplicationiscreated

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/a7623606-f3a2-4072-848c-9441681625a8)


Step12:ClickCloudShellintheKathir-Cloud-Project

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/32ae61de-99b6-43a7-9971-a998a2597f7d)


Step13:CreateaDirectoryPythonProjectusingmkdircommand

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/da7466a7-2940-44c7-8ef7-81cbf85886d9)


Syntax: mkdirPythonProject
Step14:ClickEditortocreatePython application

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/5e4e8a05-2c79-4302-9f83-556560fc0d21)


Step 15:ClickNew Filein thePythonProjectFolder(Pythonfile)

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/2197eaba-250e-4920-bf61-dcda81988437)


Step16:Createmain.pyfile

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/9c45d5cd-dae3-455d-90fd-14c99cd2c12a)


## main.pyfile
print("HelloWorld")

Step17:Createapp.yamlfile

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/4f5ea8bf-71ce-47c7-95fc-75fc2effd092)

##
## app.yaml
runtime:python27api-version:1threadsafe:falsehandlers:
url:1script:Index.py


Step18:Createrequirements.txtfile

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/725cc0c8-1c14-455b-b40f-0eae6f5cd410)


requirements.txt
Flask=
=0.11.1
gunicorn==19.6.0




Step19:MovetoCloudShellEnvironmenttoruntheapplication
![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/cc54e2f6-c503-4d45-b56f-96c1db07eb25)


Step20:MovetoCloudShellEnvironmenttoruntheapplication
Syntax:gcloudappdeploy

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/78590cb4-13d7-4ec9-b089-7b65955d238b)


Continuetheapplication.Itenableserviceonthegivenproject

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/569f8a8f-eceb-4f0c-887a-98ec4a72da95)


Itstartedbuildingtheobjectandfetchingthestorageobjectforthecreatedapplication

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/a1417443-7732-4d37-a213-2f76bc4feac3)


Itisupdatingtheservice

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/f016364c-72ba-4377-876b-eae0ce4004ac)


TheapplicationissuccessfullydeployedandURLishttps://expanded- curve-289413.uc.r.appspot.com
Step21:Run yourprograminthebrowser

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/bb2fa62c-5432-4481-8b14-c8f45eec113a)


Step22:Hello WorldProgramissucessfullyruninthebrowser

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/49eaf0f4-6730-4966-82a4-a1516d023b8d)


Result:

Thus the Google App Engine is installed successfully and a web application todisplayhelloworldusingpythonisdevelopedanddeployedintheGAEandusedGAELaunchertolaunchthe
webapplications.

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/037c6ed1-b47d-482a-8c3e-119638be16a0)


Platform asaService(PaaS)
Cloudcomputingservicewhichprovidesacomputingplatformandasolutionstack asaservice.
Consumercreatesthesoftwareusingtoolsand/or libraries fromtheprovider.
Providerprovidesthenetworks,servers,storage,etc.



GoogleAppEngine:

GoogleAppEnginewasfirstreleasedasabetaversioninApril2008.
2
5

It isaisa PlatformasaService(PaaS)cloudcomputingplatformfordevelopingandhostingwebapplicationsinGoogle-manageddatacenters.
Google‘sAppEngineopensGoogle‘sproductiontoanypersonintheworldatno
charge.
GoogleAppEngineissoftwarethat facilitatestheusertorunhiswebapplicationsonGoogleinfrastructure.
Itismorereliablebecausefailureofanyserver willnotaffecteithertheperformanceoftheenduserortheserviceoftheGoogle.
Itvirtualizesapplicationsacross multipleserversanddatacenters.
Othercloud-basedplatformsincludeofferingssuchas Amazon Web

ServicesandMicrosoft's AzureServices Platform.

IntroductionofGoogleAppEngine
GoogleAppEngineletsyourunyourwebapplicationsonGoogle'sinfrastructure. App Engine applications are easy to build, easy to maintain,andeasytoscaleasyourtrafficanddatastorageneedsgrow.WithAppEngine,there are no servers to maintain :You just upload your application, and it'sreadytoserveyourusers.
You   can   serve  your    app    from   your    own   domain    name    (suchas https://www.example.com/) using Google Apps. Or, you can serve yourapp using a free name on the appspot.com domain. You can share yourapplicationwiththeworld, orlimitaccesstomembersofyour organization.
GoogleAppEnginesupportsappswritteninseveral programminglanguages.
With AppEngine'sJavaruntimeenvironment,youcan buildyourappusingstandardJavatechnologies,includingtheJVM,Javaservlets,andtheJavaprogramming	language—oranyotherlanguageusingaJVM-basedinterpreterorcompiler,suchasJavaScriptorRuby. AppEnginealsofeaturesadedicatedPythonruntimeenvironment,whichincludesafastPythoninterpreter		and	thePythonstandardlibrary.TheJavaandPythonruntimeenvironmentsarebuilttoensurethatyourapplicationrunsquickly,securely,andwithoutinterferencefromotherappsonthesystem.
With AppEngine, you only pay for what you use. There are no set-up costsand no recurring fees. The resources your application uses, such as storageandbandwidth,aremeasuredbythegigabyte,andbilledatcompetitiverates.You control the maximum amounts of resources your app can consume, so italwaysstayswithinyourbudget.App Enginecostsnothingto getstarted. Allapplicationscanuseupto500MBofstorageandenoughCPUandbandwidth
to support an efficient app serving around 5million page views amonth,absolutelyfree.Whenyouenablebillingforyourapplication,yourfreelimits are raised, and you only pay for resources you use above the freelevels.
Architecture ofGoogleAppEngine

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/7528cfb5-e628-473e-a8a6-03d45484d109)


FeaturesofGoogleAppEngine
![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/74df22dc-a1ec-4680-a9b0-ee7cc79085bd)


GAEApplicationEnvironment:


Google App Engine makesit easy tobuild an application that runs reliably,even under heavy load and with large amounts of data. App Engine includes thefollowingfeatures:
Persistentstoragewithqueries, sortingandtransactions Automaticscalingandloadbalancing
APIsforauthenticatingusersandsendingemailusingGoogleAccounts Taskqueuesforperforming workoutsideofthescopeofawebrequest
Scheduledtasksfortriggering eventsatspecifiedtimesandregularintervals

Dynamicwebserving,withfullsupport forcommonwebtechnologies

JavaRuntimeEnvironment


You can develop your application for the Java runtime environment usingcommon Java web development tools and API standards. Your app interactswith the environment using the Java Servlets standard, and can use commonwebapplication technologiessuchasJavaServerPages
TheJavaruntimeenvironmentusesJava6.TheAppEngineJavaSDKsupports developing apps using either Java5 or 6.The environment includestheJavaSERuntimeEnvironment(JRE)6platformandlibraries.TherestrictionsofthesandboxenvironmentareimplementedintheJVM.Anappcan use any JVM byte code or library feature, as long as it does not exceedthesandboxrestrictions.Forinstance,bytecodethatattemptstoopenasocketorwritetoafilewillthrow aruntimeexception.
YourappaccessesmostAppEngineservicesusingJavastandardAPIs.Forthe AppEngine data store, the Java SDK includes implementations of the JavaDataObjects(JDO)andJavaPersistenceAPI(JPA)interfaces.Yourappcanuse the JavaMailAPItosend emailmessageswiththeAppEngineMailservice.Thejava.netHTTPAPIsaccessestheAppEngineURLfetchservice.  AppEnginealsoincludeslow-levelAPIsforitsservicestoimplementadditionaladapters,ortousedirectlyfromtheapplication.Seethedocumentationforthedatastore,memcache,URLfetch,mail,imagesandGoogleAccountsAPIs.Typically,JavadevelopersusetheJava
programming
languageandAPIstoimplementwebapplicationsfortheJVM. WiththeuseofJVM-compatiblecompilersorinterpreters,youcanalso useotherlanguagestodevelopwebapplications,suchas JavaScript,Ruby.


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/5a6b37a0-8ddd-4e28-8769-09a5011c5ec0)





WorkflowofGoogleAppEngine


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/455ab397-4001-4e65-b206-9690ae1cac1d)


Step1:Logintowww.cloud.google.com

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/1d562ec9-a9e3-4b67-8224-79e14aafffd3)


Step2:GotoConsole

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/44080c1d-2b2d-4bbb-a2a6-2d20d0da1609)


Step3:GoogleCloudPlatformisshown

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/841f00a4-ce9b-4b1d-bfe5-2ce2961562d2)


Step4:ClickDashboardintheGoogleCloudPlaform

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/241b1228-1c2d-4927-bb8d-bdec4ad9eb57)


Step5:DashboardintheGoogleCloudPlaform

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/187fafc8-95de-4a1e-8a57-6528e3467c13)


Step6:ClickNewProjectandgiveuniqueProjectName.


![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/2b526fab-c4f6-4ae3-9a73-d4218f80a9ec)


Example:kcet-cloud-project


Step7:GoogleAppEngineisinitated

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/5c2e939f-5b50-497c-ac4a-263561e7c7df)


Step8: ClickcreateApplication

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/f9111343-35f6-43af-8f68-3fbef652d29b)


Step9:CreateappandSelectLanguagePython

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/61c0f158-6d3f-49fe-a336-f9de09368630)


Step10: PythonappiscreatedinGoogleAppEngine
![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/00185cbc-03ea-433d-a263-56980040f761)


Step11 :PythonappEngineapplicationiscreated

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/a7623606-f3a2-4072-848c-9441681625a8)


Step12:ClickCloudShellintheKathir-Cloud-Project

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/32ae61de-99b6-43a7-9971-a998a2597f7d)


Step13:CreateaDirectoryPythonProjectusingmkdircommand

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/da7466a7-2940-44c7-8ef7-81cbf85886d9)


Syntax: mkdirPythonProject
Step14:ClickEditortocreatePython application

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/5e4e8a05-2c79-4302-9f83-556560fc0d21)


Step 15:ClickNew Filein thePythonProjectFolder(Pythonfile)

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/2197eaba-250e-4920-bf61-dcda81988437)


Step16:Createmain.pyfile

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/9c45d5cd-dae3-455d-90fd-14c99cd2c12a)


## main.pyfile
print("HelloWorld")

Step17:Createapp.yamlfile

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/4f5ea8bf-71ce-47c7-95fc-75fc2effd092)

##
## app.yaml
runtime:python27api-version:1threadsafe:falsehandlers:
url:1script:Index.py


Step18:Createrequirements.txtfile

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/725cc0c8-1c14-455b-b40f-0eae6f5cd410)


requirements.txt
Flask=
=0.11.1
gunicorn==19.6.0




Step19:MovetoCloudShellEnvironmenttoruntheapplication
![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/cc54e2f6-c503-4d45-b56f-96c1db07eb25)


Step20:MovetoCloudShellEnvironmenttoruntheapplication
Syntax:gcloudappdeploy

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/78590cb4-13d7-4ec9-b089-7b65955d238b)


Continuetheapplication.Itenableserviceonthegivenproject

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/569f8a8f-eceb-4f0c-887a-98ec4a72da95)


Itstartedbuildingtheobjectandfetchingthestorageobjectforthecreatedapplication

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/a1417443-7732-4d37-a213-2f76bc4feac3)


Itisupdatingtheservice

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/f016364c-72ba-4377-876b-eae0ce4004ac)


TheapplicationissuccessfullydeployedandURLishttps://expanded- curve-289413.uc.r.appspot.com
Step21:Run yourprograminthebrowser

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/bb2fa62c-5432-4481-8b14-c8f45eec113a)


Step22:Hello WorldProgramissucessfullyruninthebrowser

![image](https://github.com/DrMalathiSaravanan/Ex-6-GAE/assets/121288490/49eaf0f4-6730-4966-82a4-a1516d023b8d)


Result:

Thus the Google App Engine is installed successfully and a web application todisplayhelloworldusingpythonisdevelopedanddeployedintheGAEandusedGAELaunchertolaunchthe
webapplications.
