# REPO NAME: MRCS-Off-Hook-Detector
## License: Creative Commons Attribution-NonCommercial-ShareAlike

Provides a contact closure when phone goes off hool

intial version

The published project on the SPCoast.github.io website will
include the relevant git commit messages as a terse, high level
changelog, so don't replicate those messages here.

Many circuits used in telephony depend on knowing the state of a telephone station: whether it is on-hook or off-hook.  
Telephone people refer to this as “supervision” or in context of business telephone systems “A Lead Control.”  
In traditional office telephone systems, the “A lead” is grounded when the associated line appearance is in use.  
This ground is used to light a lamp and for control of the HOLD state.  
For model railroad telephone systems, the A lead is used to stop ringing or buzzing when a station is answered (goes off hook) 
and may be used for a busy station display where a LED or lamp lights when the associated phone is off-hook.  
Normally, when using classic telephones such as 500/554 desk and wall sets, we borrow one of the hook-switch contacts to provide an A lead.  
However not all telephones have an extra hook-switch contact, some consumer phones 
(including some retro decorator phones that have a nice transition-era look) are sealed and contacts are inaccessible 
and sometimes extra conductors are not available in the cable to the telephone.  
In those cases, it is useful to have a device which looks for current drawn on the telephone line itself and reports status accordingly 
(somewhat like a track occupancy detector).  This is the Off-Hook Detector.