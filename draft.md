
## text areas
 - abstract
 - devices
 - zones
 - teaching and hci research
 - new recent features and future work
 - references

## abstract ----- :: Abstract
Despite the fact that touch user interfaces are increasingly more ubiquitous, they generally remain inaccessible to novices and require a large amount of development overhead. The Simple Multi-Touch Toolkit (SMT) for Processing fixes that.

SMT is a simple and flexible touch user interface prototyping toolkit for the Processing environment. Its simple syntax and API opens the realm of touch to the non-coder - artists, hobbyists, and students alike.

## zones -------- :: The Interactable Zone as a UI Primitive
The concept of interactable zones as a user interface primitive is core to SMT's design. Users create new UI elements by creating 'zones' and customizing them in code. Zones can be nested in other zones, inheriting their parent's transformation matrix. This nesting is how one can create more complicated UIs, such as the swipe keyboard featured in figure 1.

## devices ------ :: Unification of Common Input Devices
In order to provide a consistent interface to the user, SMT handles all of the most common touch input devices, plus a few obscure ones. It supports the following: TUIO devices, Windows Touch, SMART SDK, and LEAP Motion. SMT also provides mouse emulation for touch events, allowing users to develop on machines that do not have touch input. Additionally, Android support is currently in development.

## usage -------- :: Use for Teaching and Research
As a teaching aid, SMT has helped students learn human-computer interaction concepts by allowing them to directly apply their knowledge. The toolkit is accessible to students of all disciplines with only basic programming knowledge.
SMT has also proved to be a powerful tool for HCI research. It has been effectively used in multiple master's thesis projects, enabling rapid development of research prototypes.
Additionally, SMT has attracted users from across the globe for various other purposes, from high school projects to interactive art displays.


## work --------- :: New Recent Features and Future Work


## architecture - :: Architecture
SMT takes full advantage of the Processing API. All zones are fully featured PGraphics objects

## references --- :: References
[1] Processing website. August 2014. http://www.processing.org
[2] TUIO website. August 2014. http://www.tuio.org
[3] TandemTable portfolio. August 2014. http://vialab.science.uoit.ca/portfolio/tandemtable

[1] Multitouch for Java (MT4j) website August 2011. www.mt4j.org
[2] PyMT website August 2011. http://pymt.eu/
[3] Kivy website August 2011. http://kivy.org/
[4] Processing website August 2011. www.processing.org
[5] TUIO website August 2011. www.tuio.org
[6] Hand from gestureworks.com/support/supported-gestures/pinch-zoom/
[7] tuioZones website August 2011. http:/jlyst.com/tz/
[8] reacTiVision website August 2011. http://reactivision.sourceforge.net/






