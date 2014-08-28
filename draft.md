## abstract ----- :: Abstract
Despite the fact that touch user interfaces are increasingly more ubiquitous, they generally remain inaccessible to novices and require a large amount of development overhead. The Simple Multi-Touch Toolkit (SMT) for Processing[1] fixes that.

SMT is a simple and flexible touch user interface prototyping toolkit for the Processing environment. Its simple syntax and API opens the realm of touch to the non-coder - artists, hobbyists, and students alike.

## zones -------- :: Zones as UI Primitives
The concept of interactable zones
as a UI primitive is core to SMT's
design. Users create new UI
elements by creating 'zones'
and customizing them in code.

Zones can be nested in other zones, inheriting their parent's transformation matrix. This nesting is how one creates more complicated UIs, such as the swipe keyboard featured in figure 1.

## architecture - :: Architecture
SMT takes full advantage of Processing's graphics API. All zones are fully featured PGraphics objects, with a few added features. To customize a zone's functionality, one can either write a function in a special form in the sketch, or extend the Zone class for extra power.

The unique feature of SMT is the ability to override functions for a Zone object with functions in the sketch. This removes the need for the user to fully understand object-oriented programming, something non-coders often find difficult to grasp.

## devices ------ :: Device Unification
SMT supports all of the most common touch input devices, plus a few obscure ones. It supports the following: TUIO[2] devices, Windows Touch, SMART Table[3], and Leap[4] Motion. SMT also provides mouse emulation, allowing users to develop on machines that do not have touch input. Android support is currently in development.
In order to provide a consistant interface to the user, SMT handles all the device management, providing a simplified 'Touch' object to the user that properly encapsulates the raw data objects.

## usage -------- :: Real World Usage
As a teaching aid, SMT has helped students learn human-computer interaction concepts by allowing them to directly apply their knowledge. The toolkit is accessible to students of all disciplines with only basic programming knowledge. SMT has also proved to be a powerful tool for HCI research. It is currently being effectively used in multiple master's thesis projects[5] at multiple universities, enabling rapid development of research prototypes. Additionally, SMT has attracted users from across the globe for various other purposes, from high school projects to interactive art displays.

## work --------- :: New Recent Features and Future Work
Recent work on SMT has been mainly focused on polish and stability. For example, SMT now supports windowed sketches and any combination of input devices. Touch rendering has been vastly improved, the zone rendering pipeline has been completely redone in a more stable manner, and more. Additionally, SMT's website and documentation have received a lot of work in order to better assist new programmers. Finally, an evaluation study has been conducted, but the analysis has not yet been completed.
  
In addition to Android support, planned future development includes support for even more input devices, a complete graphical overhaul, a layout engine, touch stabalization and smoothing, and more. Additionally, a full-fledged analysis must be completed in order conclusively determine the benefit of this toolkit. Finally, investigation into the application of SMT's strategy to domains in human-computer interaction other than multi-touch might yield interesting results.

## references --- :: References
[1] Processing website. August 2014. http://www.processing.org
[2] TUIO website. August 2014. http://www.tuio.org
[3] SMART website. August 2014. http://smarttech.com
[4] Leap Motion website. August 2014. http://leapmotion.com
[5] TandemTable portfolio. August 2014.
      http://vialab.science.uoit.ca/portfolio/tandemtable
