**Unit 1: Scientific Notation, Data Analysis, and Experimental Error**
<span id="1"></span> 
*This unit consists of a review of some basic concepts you may remember
from courses in mathematics and experimental science.  You may skim
through the material, but you will need to be precise in later work
about the nomenclature used for reporting errors and statistics.  The
reference immediately below is a handbook for engineering statistics; it
is not meant to be read from start to finish but rather to be used as a
reference for specific problems at hand.  You may wish to familiarize
yourself with the nomenclature and organization of the handbook.*

**Unit 1 Time Advisory**  
This unit should take you 19 hours to complete.

☐    Subunit 1.1: 4 hours

☐    Subunit 1.2: 6 hours

☐    Subunit 1.3: 1 hour

☐    Subunit 1.4: 2 hours

☐    Subunit 1.5: 2 hours

☐    Subunit 1.6: 1 hour

☐    Subunit 1.7: 2 hours

☐    End of Unit Self-Assessment: 1 hour

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:

-   Use scientific notation for engineering calculations.
-   Compute mean and standard deviation and understand their
    significance.
-   Compute how uncertainty in parameters propagates through simple
    calculations.
-   Perform elementary regression for parameter estimation (e.g. linear
    least-squares analysis).

-   **Reading: NIST/SEMATECH’s e-Handbook of Statistical Methods
    (2010)**
    Link: NIST/SEMATECH’s [e-Handbook of Statistical
    Methods](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.pdf)(2010)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1-National-Institute-of-Standards.epub)  
      
     Instructions: Use this handbook as a resource throughout the
    course.  Peruse the introductory material (“How To Use this
    Handbook” and “[Tools and
    Aids](http://www.itl.nist.gov/div898/handbook/)”) at this stage in
    order to facilitate later use.  
        
     Terms of Use: This material is in the public domain. 

**1.1 Numerical Precision** <span id="1.1"></span> 
**1.1.1 Scientific Notation** <span id="1.1.1"></span> 
-   **Reading: All About Circuits’ “Scientific Notation”**
    Link: All About Circuits’ “[Scientific
    Notation](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.1.pdf)”
    (PDF)  
        
     Instructions: Read the page linked above.  You may skim through the
    page if it is review for you. To view as a PDF, click the PDF link
    in the top right corner.  
        
     Terms of Use: This material has been released under the terms of
    the [Design Science
    License](http://www.allaboutcircuits.com/l_dsl.html).  

-   **Web Media: Khan Academy’s Scientific Notation 1; Scientific
    Notation 3 (new); and Scientific Notation 3**
    Link: Khan Academy’s [Scientific Notation
    1](https://www.khanacademy.org/math/arithmetic/exponents-radicals/scientific-notation/v/scientific-notation-i) (YouTube); [Scientific
    Notation 3
    (new)](https://www.khanacademy.org/math/arithmetic/exponents-radicals/scientific-notation/v/scientific-notation-3--new) (YouTube);
    and [Scientific Notation
    3](https://www.khanacademy.org/math/arithmetic/exponents-radicals/scientific-notation/v/scientific-notation-3)
    (YouTube)  
        
     Instructions: View these three videos to review the details of
    scientific notation and arithmetical operations.  You may skim
    through these topics if they are review for you.  
        
     Terms of Use: These videos are licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). They
    are attributed to the Khan Academy.

**1.1.2 Significant Figures** <span id="1.1.2"></span> 
-   **Reading: Connexions: Sunil Kumar Singh’s “Significant Figures”**
    Link: Connexions: Sunil Kumar Singh’s “[Significant
    Figures](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.2.pdf)”
    (PDF)  
        
     Also available in:  

    [PDF](http://cnx.org/content/m15032/1.3/content_info#cnx_downloads_header)  
     [EPub Format](http://cnx.org/content/m15032/1.3/?format=epub)  
     Instructions: Read these notes and pay particular attention to the
    effect of mathematical operations upon significant figures.  For
    example, consider how many significant figures might be in the
    result of the operation 1.23(4.4/6,873 +2.0).  
        
     Terms of Use: This work is licensed under a [Creative Commons
    Attribution 2.0 Generic
    License](http://creativecommons.org/licenses/by/2.0/). It is
    attributed to Sunil Kumar Singh and can be found in its original
    form [here](http://cnx.org/content/m15032/latest/). 

**1.2 Statistics** <span id="1.2"></span> 
**1.2.1 Introduction to Statistics** <span id="1.2.1"></span> 
-   **Reading: National Institute of Standards and Technology (NIST):
    Dr. W. J. Youden’s Experimentation and Measurement**
    Link: National Institute of Standards and Technology (NIST): Dr. W.
    J. Youden’s [“*Experimentation and
    Measurement*”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-0.pdf)(PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-0-W.J.-Youden.epub)  
      
     Instructions: Click the link for the PDF *Experimentation and
    Measurement* under “Calibration Related Publications.”  Read
    Chapters 4 (*Typical Collections of Measurements*) and 5
    (*Mathematics of Measurement*).  
        
     Terms of Use: This material is in the public domain. 

**1.2.2 Mean** <span id="1.2.2"></span> 
-   **Reading: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “Measures of Location”**
    Link: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “[Measures of
    Location](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.pdf)”
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1-National-Institute-of-Standards.epub)  
      
     Instructions: Read the linked section above on descriptors of
    averages.  Note that there are other descriptors (besides the mean
    and median) that may be useful.  As you read, you may wish to
    consider hypothetical cases in which the median might be more useful
    than the mean.  
        
     Terms of Use: This material is in the public domain. 

**1.2.3 Variance and Standard Deviation** <span id="1.2.3"></span> 
-   **Reading: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “Measures of Scale”**
    Link: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “[Measures of
    Scale](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.pdf)”
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1-National-Institute-of-Standards.epub)  
      
     Instructions: Read the linked section above, which presents
    descriptors of width.  The most commonly used descriptors are
    variance and standard deviation.  
        
     Terms of Use: This material is in the public domain. 

**1.2.4 Skewness and Higher Moments** <span id="1.2.4"></span> 
-   **Reading: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “Measures of Skewness and Kurtosis”**
    Link:NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “[Measures of Skewness and
    Kurtosis](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.pdf)”
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1-National-Institute-of-Standards.epub)  
      
     Instructions: Read this section on the higher moments of a
    distribution.  Under what circumstances might the higher moments be
    significant?  
        
     Terms of Use: This material is in the public domain. 

**1.3 The Normal or Gaussian Distribution** <span id="1.3"></span> 
-   **Reading: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “Normal Distribution”**
    Link: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “[Normal
    Distribution](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.pdf)”
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1-National-Institute-of-Standards.epub)  
      
     Instructions: Read the linked section on the properties of the
    Normal or Gaussian distribution.  Pay attention to the significance
    of the mean and standard deviation to the position and width of the
    distribution.  
        
     Terms of Use: This material is in the public domain. 

**1.4 Sources of Error** <span id="1.4"></span> 
-   **Reading: Simon-Fraser University: Stephen Lower’s Chem1 General
    Chemistry Virtual Textbook: “The Meaning of Measure: Dealing with
    Error and Uncertainty in Measured Values”**
    Link: Simon-Fraser University: Stephen Lower’s *Chem1 General
    Chemistry Virtual Textbook*: [“The Meaning of Measure: Dealing with
    Error and Uncertainty in Measured
    Values”](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.4.pdf)(PDF)  
        
     Instructions: Review this section, ensuring that you are able to
    distinguish between random error, systematic error, accuracy, and
    precision.  This reading addresses sections 1.4.1 and 1.4.2.  To
    view as a PDF, click the “download” link in the bottom right
    corner.  
        
     Terms of Use: This work is licensed under a [Creative Commons
    Attribution-NonCommercial 2.5 Generic
    License](http://creativecommons.org/licenses/by-nc/2.5/). It is
    attributed to Stephen Lower and can be found in its original
    form [here](http://www.chem1.com/acad/pdf/MatMeas.pdf). 

**1.4.1 Systematic Error and Accuracy** <span id="1.4.1"></span> 
**1.4.2 Random Error and Precision** <span id="1.4.2"></span> 
**1.5 Error Propagation** <span id="1.5"></span> 
-   **Reading: University of Toronto: David Harrison’s “Error Analysis
    in Experimental Physical Science”**
    Link: University of Toronto: David Harrison’s “[Error Analysis in
    Experimental Physical
    Science](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.5.pdf)”
    (PDF)  
        
     Instructions: Read the linked section above.  Answer questions
    9.1-9.4; ignore Exercise 9.1. This section is concise; you may wish
    to practice the exercises a few times.  
        
     Terms of Use: This work is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 2.0 Generic
    License](http://creativecommons.org/licenses/by-nc-sa/2.0/). It is
    attributed to David Harrison and can be viewed in its original
    form [here](http://www.upscale.utoronto.ca/PVB/Harrison/ErrorAnalysis/Propagation.html). 

**1.6 Parameter Estimates and Confidence Intervals** <span
id="1.6"></span> 
-   **Reading: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “How Are Estimates of the Unknown Parameters Obtained?”**
    Link: NIST/SEMATECH’s e-Handbook of Statistical Methods (2010):
    “[How Are Estimates of the Unknown Parameters
    Obtained?](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1.pdf)”
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.1-National-Institute-of-Standards.epub)  
      
     Instructions: Read this section and the links titled “Least
    Squares” and “Weighted Least Squares.”  This information may seem
    rather technical at the moment, but as you gain experience with
    using the methods, it will make more sense to you.  
        
     Terms of Use: This material is in the public domain. 

**1.7 Exercises** <span id="1.7"></span> 
**1.7.1 Calculation of Mean, Standard Deviation, and Variance** <span
id="1.7.1"></span> 
-   **Reading: College of St. Benedict and Saint John’s University:
    “Descriptive Statistics”**
    Link: College of St.  Benedict and Saint John’s University:
    “[Descriptive
    Statistics](https://resources.saylor.org/archived/wp-content/uploads/2011/07/ME301-1.7.1.pdf)”
    (PDF)  
        
     Instructions: Read the linked section above.  Perform the
    calculations of statistics as prompted.  You may wish to experiment
    with peculiar distributions exhibiting distinctive shapes (such as
    bimodal, triangular, or square distributions) and compare them with
    other distributions.  
        
     Terms of Use: The material above has been reposted with permission
    for educational use by Thomas W Kirkman.  It can be viewed in its
    original
    form [here](http://www.physics.csbsju.edu/stats/descriptive2.html).

**1.7.2 Linear Least-Squares Estimates of Slope and Intercept** <span
id="1.7.2"></span> 
-   **Reading: Yale University Department of Statistics’ “Inference in
    Linear Regression”**
    Link: Yale University Department of Statistics’ “[Inference in
    Linear
    Regression](http://www.stat.yale.edu/Courses/1997-98/101/linregin.htm)”
    (HTML)  
                  
     Instructions: This section caters to those with an abstract,
    mathematical bent.  You can develop some appreciation for the
    concepts involved by skimming the text and studying the graphs as
    examples rather than by trying to understand the details of the
    mathematical analysis.  Note that this material may be more
    appealing after you have some experience using the methods.  
        
     Terms of Use: Please respect any copyright and terms of use
    displayed on the webpage above.

**1.7.3 Nonlinear Regression** <span id="1.7.3"></span> 
-   **Web Media: University of Colorado’s PHET Curve-Fitting
    Demonstration Package: “Curve Fitting”**
    Link: University of Colorado’s PHET Curve-Fitting Demonstration
    Package: “[Curve
    Fitting](http://phet.colorado.edu/sims/curve-fitting/curve-fitting_en.html)”
    (Adobe Flash)  
        
     Instructions: Drag data points from the data-point-bin onto the
    graph.  Adjust the error bars.  Examine the best-fit curves for
    different situations.  You should play with this exercise to get an
    intuitive feel for how data and error bars affect the best fit
    curves.  Please also try to fit data with different types of curves
    (for example, lines and higher order polynomials).  By playing
    around with this online demo, you can quickly obtain experience that
    can be easily applied to concrete situations.  
        
     Terms of Use: This material is licensed under the [GNU General
    Public License v2.0](http://www.gnu.org/licenses/gpl-2.0.html).  It
    is attributed to [PhET Interactive
    Simulations](http://phet.colorado.edu), University of Colorado and
    the original version can be found [here](http://phet.colorado.edu/).

**Unit 1 Assessment** <span id="1.8"></span> 
-   **Assessment: The Saylor Foundation's "ME301: Unit 1 Quiz"**
    Link: The Saylor Foundation’s “[ME301: Unit 1
    Quiz](http://school.saylor.org/mod/quiz/view.php?id=916)”  
        
     Instructions: Please complete the linked assessment.  
        
     You must be logged into your Saylor Foundation School account in
    order to access this exam.  If you do not yet have an account, you
    will be able to create one, free of charge, after clicking the link.
     This quiz should require less than one hour to complete.


