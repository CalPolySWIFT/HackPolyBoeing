# HackPolyBoeing
Files for HackPoly: The Boeing Edition Competition (2019)

Hi all! This is the place where you will be able to find all files related to this competition.

Feel free to contact jennapham@cpp.edu if you have any questions.

**FAQ:**

Q: What devices will we be using?

>A: Your team is expected to use a mobile device (specifically something small like a phone) that runs iOS or Android.

Q: Which version of iOS/Android should I be developing my application for?

>A: Any version you prefer. There is no requried version.

Q: Will I be given a physical device to test my application?

>A: Yes, only if you are developing an Android app. If you are developing on iOS app then you will need to test it using your own device. **We are still waiting to receive the devices from the bookstore. Once they arrive you will be notified immediately.** For the time being an Android device and a 3D printed sample piece has been placed in a breakout room in the CBA (163-1010). You should have access to this room - if you do not please email jennapham@cpp.edu with your CPP email & Bronco ID ASAP.

Q: Do I need to register for Tech Symposium?

>A: No. Someone from the SWIFT E-Board has already registered you.

Q: Do I need to be present at Tech Symposium?

>A: Yes the ENTIRE team must be present for the during of the competition. The exact times will be announced at a later date.

Q: Will we be given a data set to train our object detection model or do we have to somehow get it ourselves?

>A: We are going to generate a few snapshots from 3D CAD models but it won’t produce a large enough sample to train a CNN model. I suggest that the students use data augmentation to generate similar images from what we provide to increase their sample size.

Q: It was mentioned that there would be stickers placed on the part and we would have to determine the coordinates of the sticker (relative the origin point that Boeing will set) and piece the sticker is on. What kind of stickers are these?

>A: These stickers are simply markers - they do not contain a QR code or anything of the like.

Q: What software can we use to open the .stp file?

>A: You can use https://viewer.autodesk.com/ to open and view the .stp files. This does not require you to download anything and is completely free. All you have to do is register for an account.

**The following questions and answers are from the meeting with the Boeing Engineers on March 27, 2019.**

If you would like to listen to the recording, you can do so here: https://youtu.be/9Obaf0iFVFw

Q: What kind of stickers are you guys using to mark the focal points on the parts? If they are something special, will competitors be given access to them before hand?

>As we think about it, you can be out buying a million different parts for an airplane and we want you to be able to train your system to be able to pick up any type of color or any type of badge. And also, as we were thinking about it further, we may actually say, "Hey identify the corner of this part" or something like that. So we don't want you to train your software for a specific sticker. We want you to train it to pick up anything. So the answer is, no we're not going to give you access to anything ahead of time.

>So the idea with the sticker was, you know, if you're investigating an area and there is a little piece of corrosion there, we want the software to be able to tell, "hey there's an area that looks like there's some corrosion, what are the coordinates for it?" So that would be one of the functions that the software would do. The other function is recognize parts and you have a fastner that needs to be replaced and so we'll have little fastner heads in the printed model, that we (Boeing) give you and so recognizing the head of a hex bolt or something like that. So it's more geometry based than it is a flat sticker.

Q: The goal is to detect corrosion but at this point do you want the tool to detect corrosion? Or just detect what part it is that has corrosion? Will corrosion detection be done manually?

>Yeah the corrosion would be the operator looking through the device, IDs an area of suspicion and so the software doesn't need to recognize the corrosion, it just needs to see where the
crosshairs pointed at.

>I think it's more where you point the crosshair on the assembly it'll give you the location on that software. It could be something where somebody sees a crack forming, you have to know location. See there’s some hydraulic fluid or some grease leaking from a joint and so where is that. It should automatically mark it in some other database, like a maintenance database system.

>Because right now one of the problems we have is most of the people that are maintaining these Air Force airplanes, they only have a high school degree and it's like you're going out to change the oil in your car but we're telling them to do all this documentation and they're like I just want change the oil in the car and go play pool. The paperwork is a pain in the rear.
