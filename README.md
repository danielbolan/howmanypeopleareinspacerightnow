# How many people are in space right now?

I was sad when I first realized that [howmanypeopleareinspacerightnow.com](https://howmanypeopleareinspacerightnow.com) was no longer updating, since the [MagTag](https://www.adafruit.com/product/4800) I was using as a desktop display would no longer work properly.

Then I came across [Supercluster's wonderful astronaut database](https://www.supercluster.com/astronauts?ascending=false&inspace=true&limit=63&list=true&sort=launch%20order) and knew it would be perfect to get my display working again. However, they dump the full 5MB+ of JSON on you which would quickly overwhelm the MagTag's ESP32. This is a lunchbreak-sized reimplementation to parse things down to something smaller and get things up and running again.

Updates every day at about 01:53 UTC.