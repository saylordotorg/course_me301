**Unit 4: Computer Assisted Data Acquisition** <span id="4"></span> 
*Current data acquisition methods often employ electronic signal
transduction and digital recording for subsequent analysis.  Since these
methods are so widespread and since errors in inappropriate
implementation may manifest differently than they would if you were to
make the same mistake reading a meter, you should understand some of the
details of the process and some of the common artifacts of inappropriate
implementation.  Consider, for example, the differences between an
artifact observed in imperfect digital versus imperfect analog imagery
or audio reproduction.*  
  
 *Note: Much of the material in Units 3 and 4 are interdependent and
refer you to material in “*[*All About
Circuits*](http://www.allaboutcircuits.com/vol_3/index.html)*”; you are
encouraged to peruse that resource in full at your own pace if you are
not familiar enough with concepts in electrical engineering to
understand the material as it is presented here.*

**Unit 4 Time Advisory**  
This unit should take you 11 hours to complete.

☐    Subunit 4.1: 4 hours

☐    Subunit 4.2: 1 hour

☐    Subunit 4.3: 1 hour

☐    Subunit 4.4: 4 hours

☐    End of Unit Self-Assessment: 1 hour

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:

-   Distinguish between analog and digital signals.
-   Apply the concepts of bandwidth, sampling rate, and digital
    resolution to practical data acquisition problems.
-   Gain familiarity with a typical computer-based data acquisition
    system.

**4.1 Analog Signal Processing** <span id="4.1"></span> 
-   **Reading: All About Circuits: “Volume 1, Chapter 9: Analog and
    Digital Signals”**
    Link:  All About Circuits: “[Volume 1, Chapter 9: Analog and Digital
    Signals](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-1.1.1.pdf)”
    (PDF)  
        
     Instructions:  This section should provide you with enough
    background information to understand analog signals in general and
    pneumatic and electrical signals in particular.  The analogy between
    fluid and electrical systems may appeal to those with practical
    fluid mechanics experience. To view as a PDF, click the PDF link in
    the top right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

**4.1.1 Signal Waveforms** <span id="4.1.1"></span> 
-   **Reading: All About Circuits: “Volume 2, Chapter 1: Basic AC
    Theory” and “Volume 2, Chapter 7: Mixed-Frequency Signals”**
    Link: All About Circuits: “[Volume 2, Chapter 1: Basic AC
    Theory](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-vol-2.pdf)”
    (PDF) and “[Volume 2, Chapter 7: Mixed-Frequency
    Signals](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-vol-2.pdf)”
    (PDF)  
        
     Instructions: These sections introduce alternating current (AC)
    signals.  The material is rich; you may wish to revisit the sections
    after the initial study.  The main idea is that steady signals
    permit the communication of only one piece of information: the
    amplitude of that signal.  By combining that amplitude with
    measurements of time, we can communicate a new piece of information
    at each new time.  Schemes for encoding information into signal
    amplitude and time variation can be quite complex; take, for
    example, the different communication protocols for radio,
    television, cellular telephone, etc.  In order to understand these
    technologies, you must have a firm grasp of the underlying physics
    and mathematics of time-varying signals.   
      
     You should first skim the above sections and flag any topics or
    symbols that you do not understand.  You may then revisit these
    sections after you have completed both Units 3 and 4 in their
    entirety. To view as a PDF, click the PDF link in the top right
    corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

**4.1.2 Voltage and Current Signal Systems** <span id="4.1.2"></span> 
-   **Reading: All About Circuits: “Volume 1, Chapter 9: Current Signal
    Systems” and “Voltage Signal Systems”**
    Link: All About Circuits: “[Volume 1, Chapter 9: Current Signal
    Systems](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-1.1.1.pdf)”
    and “[Voltage Signal
    Systems](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-1.1.1.pdf)”
    (PDF)  
        
     Instructions: Read these sections; they introduce the ideas and
    circuit symbols for ideal current and voltage sources and present
    background material on their utility and non-idealities.  At a
    minimum, upon completing this reading, you should be familiar with
    the symbols involved for future study. To view as a PDF, click the
    PDF link in the top right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

**4.1.3 Filtering** <span id="4.1.3"></span> 
-   **Reading: All About Circuits: “Volume 2, Chapter 8: Filters”**
    Link: All About Circuits: “[Volume 2, Chapter 8:
    Filters”](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-vol-2.pdf)(PDF)  
        
     Instructions: Read the linked chapter on filters.  The text is
    sufficiently self-explanatory and contains an introductory
    discussion.  You might wish to keep in mind the following questions:
    How can digital signal processors be used to build filters?  Is it
    necessary to use analog filtering devices? To view as a PDF, click
    the PDF link in the top right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

**4.1.4 Bridge Circuits** <span id="4.1.4"></span> 
-   **Reading: All About Circuits: “Volume 1, Chapter 8: DC Bridge
    Circuits” and “Volume 2, Chapter 12: AC Bridge Circuits”**
    Link: All About Circuits: “[Volume 1, Chapter 8: DC Bridge
    Circuits](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-1.1.1.pdf)”
    (PDF) and “[Volume 2, Chapter 12: AC Bridge
    Circuits](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-vol-2.pdf)”
    (PDF)  
        
     Instructions: Read the linked sections above and perform
    measurements as possible.  You needn’t become an expert at bridge
    design, but rather your aim should be to become familiar with the
    terminology and use of bridge circuits. To view as a PDF, click the
    PDF link in the top right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

**4.2 Digitization** <span id="4.2"></span> 
-   **Reading: All About Circuits: “Volume 4, Chapter 13: Introduction
    to Digital-Analog Conversion”**
    Link: All About Circuits: “[Volume 4, Chapter 13: Introduction to
    Digital-Analog
    Conversion](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-vol-4.pdf)”
    (PDF)  
        
     Instructions: Read the linked section above for an introduction to
    relevant terminology.  You should understand the relationship
    between analog signals, digital signals, and binary numbers. To view
    as a PDF, click the PDF link in the top right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

-   **Reading: All About Circuits: “Volume 4, Chapter 13: Practical
    Considerations of ADC Circuits”**
    Link: All About Circuits: [“Volume 4, Chapter 13: Practical
    Considerations of ADC
    Circuits](http://www.saylor.org/site/wp-content/uploads/2011/07/ME301-vol-4.pdf)”
    (PDF)  
        
     Instructions: Read the linked section.  Focus on the two topics
    (i.e. the headings for subunits 4.2.1 and 4.2.2) listed below.  For
    example, you might keep the following questions in mind: What is the
    percent linear resolution in a 24-bit binary encoding? How often
    must sound be sampled in order to accurately represent 20 kHz
    signals to the ear? To view as a PDF, click the PDF link in the top
    right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

**4.2.1 Number of Bits or Resolution** <span id="4.2.1"></span> 
**4.2.2 Sampling Rate** <span id="4.2.2"></span> 
**4.3 Common Artifacts from Improper Digitization** <span
id="4.3"></span> 
*Note: The most common artifacts from digitization occur as a result of
inappropriate sampling rate and/or signal amplitude.  In principle,
these problems are similar to, for example, seeing only every hundredth
frame in a video presentation or having the volume knob up way too high
on an audio presentation.  There are, however, many other subtle
artifacts which may emerge upon close scrutiny.  You may be familiar
with the vast difference in the sorts of problems that occur with
digital television or cell phone transmission versus analog
transmission.  Likewise, problems may manifest differently depending
upon the processing that is used to get from the original digital signal
to the result.*  
    
 *For a more detailed theoretical discussion of this topic, you may
refer to Unit 15 of* *[ME205: Numerical Methods for
Engineers.](../../courses/me205/) *(HTML)

**4.4 Tutorial for a Commercial Data Acquisition System** <span
id="4.4"></span> 
-   **Reading: National Instruments’ LabVIEW Tutorials: “LabVIEW
    Basics”**
    Link: National Instruments’ LabVIEW Tutorials: “[LabVIEW
    Basics](http://www.ni.com/gettingstarted/labviewbasics/)” (HTML and
    Adobe Flash)  
        
     Instructions: Familiarize yourself with the capabilities of this
    virtual instrumentation environment.  This is an example of common
    functionality for such a system in a laboratory.  If you have access
    to a similar system, take the time to acquaint yourself with it.   
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).

**Units 3 and 4 Assessment** <span id="4.5"></span> 
-   **Assessment: The Saylor Foundation's "ME301: Units 3 and 4 Quiz"**
    Link: The Saylor Foundation's
    ["](http://www.saylor.org/site/wp-content/uploads/2011/02/ME301-UA-3and4-FINAL.pdf)[ME301:
    Units 3 and 4
    Quiz](http://school.saylor.org/mod/quiz/view.php?id=918)"  
      
     Instructions: Please complete the linked assessment.  
        
     You must be logged into your Saylor Foundation School account in
    order to access this exam.  If you do not yet have an account, you
    will be able to create one, free of charge, after clicking the
    link. 


