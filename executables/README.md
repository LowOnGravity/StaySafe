<div align="center"> 

[How to find webhook in a python executable?](https://github.com/StaticPerson/StaySafe/tree/main/executables/python%20executables)

#


Tools used:

  
  * [.NET Webhook Finder](https://github.com/DeLuxe-1337/.NET-Webhook-Finder)
  
  * [Webhook Remover](https://github.com/venaxyt/Discord-WebHook-Deleter)
  
  * [DnSpy](https://github.com/dnSpy/dnSpy)

  My todays target will be a software pretending to be a "XPCheat" 
  
  > which is obviously just an stealer.
  >
 >  ![image](https://user-images.githubusercontent.com/96681438/218167932-89e4e8e2-3668-4af5-9a9c-07123a86006c.png)




# Simple steps
  
  Make sure to NEVER run such executables on your computer, as it might be more than just a stealer.
  
 Begin with using [Virustotal](https://www.virustotal.com/gui/home/upload)


  > ![image](https://user-images.githubusercontent.com/96681438/218165581-b3b2b549-d4c0-441c-813c-bde0d83a0289.png)
>
  >
 > **Always take it into consideration that even one detected irregularity should be a sign to not run it.**
  
  Do not forget to take a look at a process tree included in Behaviour Tab.
  >
 > ![image](https://user-images.githubusercontent.com/96681438/218166015-36bde19c-1ba3-4c9e-a849-5671b8033bee.png)

You can clearly see that one of its main elements is called "Webhooks" and it messes up with things around your System32 folder.
  
 Let's try using .NET webhook detector to see what's up.

>  It's usage is pretty simple, just drag your executable into CMD window.
  >
>  ![image](https://user-images.githubusercontent.com/96681438/218166446-ab071c4a-3ac3-4b50-9024-41035faf64c2.png)

Now, it is clear that it is simply just a stealer, let's take some steps to delete it!
  
> ![image](https://user-images.githubusercontent.com/96681438/218166738-2ef1aa7a-1a15-4f9a-bd2d-78025f430f5a.png)
>
  > Simply copy paste such token and press enter, it should be done!

It is not something you should do, but to prove you that it's main modules are just called "webhooks" I will use DnSpy to view some .NET modules:
  
 ![image](https://user-images.githubusercontent.com/96681438/218167151-e4b47937-f88e-402f-969b-cc2c5aa615eb.png)


</div>
