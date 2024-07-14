# JoSAA Counselling
 The Joint Seat Allocation Authority (JoSAA) 2022 has been set up to manage and regulate the joint seat allocation for admissions to 6 institutes for the academic year 2022-23. This includes 2 IITs, 2 NITs, 2 IIITs. Admission to all the academic programs offered by these Institutes will be made through a single platform.
        
We have created a mini replica of the JOSAA counselling system in which we will be able to:
        <ul>
            <li>Apply for JOSAA Counselling</li>
            <li>Check opening and closing ranks</li>
            <li>Check the Scheduled Events and Business Rules</li>
        </ul>

### Features of Our System

  <ul>
            <li>In our system we have two rounds of the admission process.</li>
            <li>We have included reservations for OBC and Physically Handicapped students.</li>
            <li>Following is the list of Institutes and branches we have included in our counselling:
                <ul>
                    <li> IIT Bombay – CSE, ASE (Aerospace Engineering)</li>
                    <li> IIT Madras – CSE, ME (Mechanical Engineering)</li>
                    <li> NIT Trichy – CSE, ECE (Electronics Communication and Engineering)</li>
                    <li> NIT Surathkal – CSE, AI (Artificial Intelligence)</li>
                    <li> IIIT Allahabad – IT, IT-BI (Business Informatics)</li>
                    <li> IIIT Gwalior – CSE, Integrated MTech IT, Integrated MBA</li>
                </ul>
            </li>
            <li>We have independent functions to display the Scheduled Events and Business Rules.</li>
            <li>We will display opening and closing ranks for the two rounds based on the candidates' choices.</li>
        </ul>

###  Process Overview

<ul>
            <li>We store the details of the student.</li>
            <li>Based on the candidate's qualification, we print the list of eligible institutes.</li>
            <li>Then we store the candidate's top 3 choices.</li>
            <li>Now we check whether the candidate's rank lies between the opening and closing rank of their preferred choice of institute and branch for the respective round.</li>
            <li>Based on steps 3 and 4, Round 1 seat is allotted to the student.</li>
            <li>Candidate has to choose whether they want to Float/Freeze their seat.</li>
            <li>If Freeze is chosen as the option, then the seat is allotted and the candidate will not be allowed to participate in the next round.</li>
            <li>If Float is chosen, then based on steps 3 and 4, Round 2 seat is allotted to the student.</li>
            <li>This is the final allotted seat.</li>
        </ul>
 



