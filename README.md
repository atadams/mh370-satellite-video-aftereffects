This is After Effects files for a recreation of the [MH370 Satellite video](https://web.archive.org/web/20140827052109/https://www.youtube.com/watch?v=5Ok1A1fSzxY) that I originally [posted on Reddit](https://www.reddit.com/r/AirlinerAbduction2014/comments/18uw8v4/my_recreation_of_the_mh370_satellite_video_using/).

To render the animation you will need the following paid plugins and models:

* [Element 3D](https://www.videocopilot.net/products/element2/) from Video Copilot
* [JetStrike Model Collection](https://www.videocopilot.net/products/3d/jetstrike/) from Video Copilot
* [Particular](https://www.maxon.net/en/red-giant/trapcode/particular) from Maxon (part of Red Giant Trapcode)

Note: all three of these were available in 2014 (when the original video was believed to have been made.)

# Reddit Post

I'm OK at VFX. Far from a pro. I just do things for fun. This took me a bit of time, but most of that was me learning and a lot of time trying to match the look of the original. I think I could redo this in a day. There was nothing complicated about it at all. Every feature I used was available in 2014.

## Cloud Textures

There is no doubt in my mind the [Textures.com images](https://www.textures.com/download/Aerials0028/75131) were used for the clouds. They are exact matches. Piecing them together in Photoshop was simple. Although they don't align perfectly with the video, the person who did this originally probably warped the images and it’s impossible to replicate that. But the details are all the same.

I then added the Exposure filter and adjusted the hue and saturation and I had 95% of what is in the original video. The other 5% was trying to match the color and levels of the original. There are infinite variations to adjust an image, so, again, matching it exactly is impossible.

Turning the exposure filter way up is what gives the clouds that blown out look. It clips the brightest pixels and makes them white.

## Plane & Contrails

The clouds were used as the background for a 3D After Effects composition. The plane and contrails were straight from the [Video Copilot tutorials](https://www.videocopilot.net/flightschool/). I used their Elements 3D plugin and [JetStrike Model Pack](https://www.videocopilot.net/products/3d/jetstrike/), which includes a Boeing 777 model (and, BTW, a Predator drone model). I used Trapcode Particular for the contrails. The details are in the [VC tutorial](https://www.videocopilot.net/flightschool/jet_contrails/).

The 777 model from JetStrike plane doesn't match the plane in the original, but the plane in the original doesn't look like a 777 to me. I'm not sure what was used.

I set up a basic 3D camera and had it orbit around a point. I use the rotation parameter on the plane to make it bank. In the video, the plane breaks out of circular turn when it’s perpendicular to the camera. It then goes a little more straight. This was simple keyframed adjustments in the rotation, bank, and position. Once again, matching the original was much more time consuming than

I had to spend some time getting the scene to match the original (e.g., scale, camera angles). This is obviously something the original creator wouldn't need to do. It would probably take 90 minutes to set that up if you knew what you were doing.

## Orbs

I used Element 3D again for the orbs. I set up a simple sphere primitive in the extension. It allows you to duplicate an object and manipulate each individually or as a group. I attached the group to the plane and set a constant rotation around the plane. I used keyframes to position the individual orbs so they each could make their entrance. This was as simple as dragging an orb off the stage. Once the 3 orbs had made their entrance and were rotating around the plane, I started to rotate them slowly on the other 2 axes. This gives the effect seen in the original of the orbs rotating all around the plane. I slowed those 2 axes rotations as the plane neared the end point until the only rotation was around the middle of the plane. This is how the orbs seem to look like they are aligning to open the portal. It looks complicated, but it really was as simple as moving to a point in the timeline and adjusting the rotation parameters.

## Portal Flash

The portal flash is a frame from the SHOCKWV.MOV file in the Pyromania stock explosion package. This is the same file that the portal from infrared video uses. THIS IS NOT A COINCIDENCE. These videos are VFX.

I had to adjust the levels of the image and applied a camera warp, but it matches.

To get the flash of the portal, I added some glow, adjusted the levels, and added the CC Light Rays effect. I added a second CC Light Rays effects but masked to the clouds surrounding the portals. This gives the localized flash seen in the original. The mask gives the appearance of dimension on the clouds when they are brightened, but it's a simple mask that's achieving that.

## Mouse & Coordinates

If I were doing this from scratch, I’d just screen record me interacting with the video to get the mouse movements and panning, but it was more complicate to match the mouse movements from the original.

I used Boris FX’s Mocha to track the motion of the panning from the original and applied that to position of my 3D scene (i.e., it panned it). I used After Effects’ Motion Tracker to track the mouse pointer from the original and applied it to the position a mouse PNG I drew.

To get the coordinates to display, I used the technique [/u/GodDestroyer](https://www.reddit.com/u/GodDestroyer/) described in [this thread](https://www.reddit.com/r/AirlinerAbduction2014/comments/16lzmk5/comment/k15rfeh/?context=3&share_id=NG4slNMo4LTpJLKr9opO9&utm_content=1&utm_medium=ios_app&utm_name=ioscss&utm_source=share&utm_term=1). I synced the change in coordinates with the panning of the video. That took about an hour.

## Misc

I added the Gaussian Blur and Turbulent Noise effects to match the original. Adding these time of effects to grunge up a video is a common trick in VFX to hide a lot of stuff that doesn't look right.

The render took about an hour on my 2.5 year old iMac. As I said, I’m not extremely experienced After Effects and don’t know all the tricks to optimize a project and speed up renders.

## Why?

I wanted to do this for a few reasons. First, I've been wanting to get more experience with After Effects’ 3D features and this was a good opportunity. It took some time, but I learned a lot. And that’s alway good.

Second, I’m very concerned that, especially with AI, we will see more and more faked images and videos that are very convincing. I know I’m being more skeptical than I was a few years ago (and I was big skeptic then).

Third, I wanted to learn how these videos were done and share that with anyone who was interested.