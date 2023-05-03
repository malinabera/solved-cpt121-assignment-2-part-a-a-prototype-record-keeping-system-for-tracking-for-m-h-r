Download Link: https://assignmentchef.com/product/solved-cpt121-assignment-2-part-a-a-prototype-record-keeping-system-for-tracking-for-m-h-r
<br>
<strong>This assessment requires you to apply various concepts and techniques covered in weeks 1-8 of the course, to </strong><strong>assemble a programmatic solution for a problem based on a simulated real-world scenario.</strong>

<strong>An important part of your development as a programmer is the ability to identify and apply appropriate techniques </strong><strong>or programming structures when implementing the various aspects of a programmatic solution to a given problem, </strong><strong>so in addition to the basic functional requirements of this task, you will also be assessed on your ability to select and utilise appropriate techniques and structures in your solution.</strong>

<strong>This assessment requires you to design and create a Java program to solve analysed stakeholder (user and </strong><strong>supervisor) requirements.</strong>

<strong>Course learning outcomes</strong>

<strong>This assessment is relevant to the following course learning outcomes:</strong>

<ul>

 <li><strong>CLO 1: Solve simple algorithmic computing problems using basic control structures and Object-Oriented </strong><strong>Techniques</strong></li>

 <li><strong>CLO 2: Design and implement computer programs based on analysing and modelling requirements</strong></li>

 <li><strong>CLO 3: Identify and apply basic features of an Object-Oriented programming language through the use of </strong><strong>standard Java (Java SE) language constructs and APIs</strong></li>

 <li><strong>CLO 4: Identify and apply good programming style based on established standards, practices and coding </strong><strong>guidelines</strong></li>

 <li><strong>CLO 5: Devise and apply strategies to test the developed software</strong></li>

</ul>

<strong>Assessment details</strong>

<strong>‘Moolort Heritage Railway’ (MHR) is a (fictional) volunteer steam locomotive railway. They have recently </strong><strong>diversified their operations into offering paid </strong><strong><em>events </em></strong><strong>(such as demonstrations) to adult rail enthusiasts on topics such as ‘Firing a Steam Locomotive’ and ‘Rail signalling’.</strong>

<strong>MHR has encountered difficulty maintaining accurate records for this new venture. Your task is to produce, </strong><strong>using standard Java (Java SE), a prototype record keeping system for tracking which events are on offer and </strong><strong>who has registered for them.</strong>

<strong>Interviews with three Moolort Heritage Railway volunteers are given below. You should analyse the </strong><strong>interviews to determine the functional requirements for your program. Your supervisor has provided </strong><strong>further requirements. These requirements are set out in the three stages </strong><strong><em>(A, B </em></strong><strong>and </strong><strong><em>C) </em></strong><strong>below. Since each </strong><strong>stage elaborates on the previous one, you only need to submit one program — the one implementing the </strong><strong>highest stage you were able to complete.</strong>

<strong>The functionality of each stage will be tested on test-case described in </strong><strong><em>TestCases.pdf, </em></strong><strong>which can be found </strong><strong>on the course Canvas under the </strong><strong><em>Assignment 2 </em></strong><strong>link.</strong>

<strong>For each of the stages </strong><strong><em>A, B </em></strong><strong>and </strong><strong><em>C, </em></strong><strong>complete the steps below based on the Double Diamond process: </strong><strong>Discover</strong>

<strong>‘Go wide’ in the form of reading and thinking about the supplied stakeholder requirements. Find out what </strong><strong>the current situation is and understand user behaviours and business drivers.</strong>

<strong>Fill in the supplied ‘Discover and Define’ Word template with a list of different problems that could be </strong><strong>solved.</strong>

<strong>Define</strong>

<strong>From your understanding of the overall issues/requirements, narrow down to a single problem and turn that </strong><strong>into a problem statement. The problem statement defines what you will develop, and you may start some </strong><strong>initial coding to start working out if you can create a solution to the problem you defined.</strong>

<strong>Fill in the supplied ‘Discover and Define’ Word template with a statement of the single problem you will </strong><strong>solve.</strong>

<strong>Develop</strong>

<strong>Start coding to create an initial prototype and program logic to address the problem. You may create a few </strong><strong>different iterations to get to the best prototype. This is a phase for trying ideas out to see if they work.</strong>

<strong>Deliver</strong>

<strong>Pick the best prototype from the ‘Develop’ phase and create the final version of the code, refining and </strong><strong>making it work. The aim is to create a minimum viable product (MVP) to address the problem you have </strong><strong>identified and defined. The final result of this process at stage </strong><strong><em>C </em></strong><strong>will become your final submission for </strong><strong>assessment 2.</strong>

<strong>How to use the Double Diamond is explained in the course webinar, please ask your instructor if you have </strong><strong>any questions.</strong>

<strong>The assessment is marked out of a total of 10 marks as given in the rubric criteria table at the end of this </strong><strong>document.</strong>

<strong>Coding style/documentation</strong>

<strong>Your program must follow the coding and documentation style guide given in the file <em>StyleGuide.pdf, </em></strong><strong>available on the course Canvas under the <em>Assignment 2 </em>link.</strong>

<strong>Stage </strong><strong><em>A </em></strong><strong><em>— </em></strong><strong>Modelling and implementing a class to represent a demonstration</strong>

<strong>Your task here is to discover and define the problem and then develop a Java program which implements the </strong><strong>functional requirements derived from the interviews and instructions given below.</strong>

<strong>Clem — Railway Manager</strong>

<strong><em>“We now offer demonstrations once a month, on the same day as our rail service. The </em></strong><strong><em>demonstrations have increased our patronage, since it has provided a point of difference between us </em></strong><strong><em>and other heritage railways. Originally, we didn’t charge a fee, but including it reduced no-shows and </em></strong><strong><em>ensured participants were real rail enthusiasts. We need help keeping track of the demonstrations we are offering for the upcoming month. As a proof of concept, in this stage, we’d like you to be able to </em></strong><strong><em>model and display a single demonstration, and reservations for that demonstration.”</em></strong>

<strong>Ian — Programme Event Manager</strong>

<strong><em>“For the foreseeable future, we only offer any particular demonstration once a month. We decide </em></strong><strong><em>what demonstrations we will offer in the coming month at our monthly MHR meeting. There we </em></strong><strong><em>determine the relevant details: what the title should be, what time it starts (which would be at the </em></strong><strong><em>start of an hour), how many minutes we expect it to go for, the base fee we are going to charge and how many attendees we can have. A demonstration’s title can be ungainly, so we refer to them using </em></strong><strong><em>a shorthand identifier. I’d like to be able to see a nice formatted tabulated display of information for </em></strong><strong><em>a demonstration.”</em></strong>

<strong>Robert — Ticket Officer</strong>

<strong><em>“We charge patrons for attending a demonstration. What the fee is depends on a couple of factors. </em></strong><strong><em>First there is the base fee of the demonstration, but patrons don’t always have to pay that amount. I </em></strong><strong><em>mean, if they are concession card holders, they get a ten percent discount off the base fee. We have </em></strong><strong><em>discount arrangements with three steam rail societies. Feilding Steam Rail Society (FSRS) members </em></strong><strong><em>get a twenty percent discount and Australian Railway Historical Society (ARHS) members get a </em></strong><strong><em>twenty five percent discount. For members of our own society, MHR, a demonstration is free, which is </em></strong><strong><em>a nice benefit. Discounts/concessions aren’t cumulative. If a patron qualifies for more than one, we only give the highest one that they qualify for. For each demonstration, I need to be able to record </em></strong><strong><em>when someone reserves a place, then figure out how much to charge them. To record a reservation, </em></strong><strong><em>after I’ve checked there is a place available, I collect their name and contact phone number, and </em></strong><strong><em>record that against the demonstration they want to attend. I also record how much they were </em></strong><strong><em>charged as sometimes people cancel their reservation and I need to know how much to refund to </em></strong><strong><em>them.”</em></strong>

<strong>Your supervisor advises that your program should be able to use object-oriented techniques to model and display a single ‘demonstration’ with reservations as described above. Your program should also test and </strong><strong>display the ‘demonstration’ fee calculation for each possible discount (including none) using stage <em>A </em>data </strong><strong>from the <em>TestCases.pdf </em>file. No user input should be required by your program.</strong>




<strong><em>0</em></strong><strong> RMIT</strong>

<strong>UNIVERSITY</strong>

<strong>You are expected to adhere to all relevant object-oriented programming guidelines, including:</strong>

<ul>

 <li><strong>Visibility of instance variables and methods set appropriately</strong></li>

 <li><strong>Instance variable initialisations carried out in the constructor only</strong></li>

 <li><strong>No unnecessary accessors (setters) or mutators (getters) – only provide methods which will be </strong><strong>needed when implementing the application class in this stage</strong></li>

 <li><strong>Methods should work with instance variables when performing their required task</strong></li>

 <li><strong>Parameter lists in methods should be appropriate to the task the method is performing – only accept </strong><strong>parameters where a method requires one or more values from the caller to perform its assigned task </strong><strong>that it does not already have access to</strong></li>

 <li><strong>Methods which need to communicate a value or result back to the caller should do by returning the </strong><strong>value in question, not by storing it in an instance variable or printing it to the screen</strong></li>

 <li><strong>Data classes should not prompt for input from the user</strong></li>

</ul>

<strong>Stage <em>B </em></strong><strong>— </strong><strong>Programme management system</strong>

<strong>In this stage, you will discover and define the problem specific to this stage, and implement a console-driven </strong><strong>application in Java which provides functionality to the users, allowing them to enter, store and manage information about multiple ‘demonstrations’ in the system. A summary of the user interviews in which </strong><strong>requirements for this stage were presented is given below.</strong>

<strong>Ian — Programme Event Manager</strong>

<strong><em>“I’d like the capability to add up to five demonstrations to the system, possibly more in future, but</em></strong>

<strong><em>five is enough for this prototype. I’d also like to be able to choose to display them — either a </em></strong><strong><em>particular demonstration whose identifier I specify, or to display all of them. I need a way to find out </em></strong><strong><em>simple statistics about attendance at our demonstrations, specifically which demonstration(s) has the lowest attendance and what that number is, which has the highest and what the average </em></strong><strong><em>attendance is. A nice formatted tabulated report with this information would be very useful. The</em></strong>

<strong><em>report doesn’t need to list the full demonstration title, just the identifier would be enough.”</em></strong>

<strong>Robert — Ticket Officer</strong>

<strong><em>“I get enquiries about what demonstrations are on offer and how many places are left so I need to </em></strong><strong><em>be able to access that information. It should also tell me what reservations have been made, as </em></strong><strong><em>sometimes participants forget what they are attending. I need to be able to remove a reservation </em></strong><strong><em>too, since sometimes participants cancel.”</em></strong>

<strong><u>Important:</u></strong><strong> Your supervisor advises that your program must utilise a single </strong><strong><u>array</u></strong><strong> for storing information </strong><strong>about all the demonstrations, in a class called <em>ProgMgmtSys. </em>Collections must not be used. The </strong><strong><em>ProgMgmtSys </em></strong><strong>class should provide a user-friendly menu to allow the user to perform tasks relevant to the needs expressed in interviews, above. Your program should be able to handle conditions such as searching </strong><strong>for a demonstration that doesn’t exist, attempting to overbook a demonstration, attempting to remove a </strong><strong>non-existent reservation, or to store too many demonstrations as specified in stage <em>B </em>cases from the </strong><strong><em>TestCases.pdf </em></strong><strong>file. You are expected to adhere to all relevant object-oriented programming guidelines, as </strong><strong>described in stage <em>A.</em></strong>

<strong>Stage <em>C— </em>Managing demonstration reservations</strong>

<strong>In this stage, you will discover and define the problem specific to this stage, and extend the console-driven </strong><strong>application from stage <em>B </em>to include a new event offering by MHR: workshops. A summary of the user interviews in which requirements for this stage were presented is given below.</strong>

<strong>Ian — Programme Event Manager</strong>

<strong><em>“We want to offer hands-on workshops. This type of event is like a demonstration, but there are a </em></strong><strong><em>few differences that mean our current system can’t handle them. Can you alter the prototype to</em></strong>

<strong><em>handle workshops as well as demonstrations? A workshop requires all the same details as a </em></strong><strong><em>demonstration. But in addition, a workshop has a materials charge that we add to the participants </em></strong><strong><em>fee. We’d also like to record a one-line description setting out any other requirements for the </em></strong><strong><em>workshop, such as the need to wear closed-toe footwear. We’d like the workshop display to include the materials charge and the requirements. Since the two types of event are so similar, I don’t need </em></strong><strong><em>to distinguish between them in the statistics report. I also don’t want separate menu options for </em></strong><strong><em>adding workshops, displaying them or getting statistics — I’d prefer the existing options be modified so they can handle workshops too. “</em></strong>

<strong>Robert — Ticket Officer</strong>

<strong><em>“The process for reserving a workshop place is very similar to that for a demonstration, so I don’t want additional menu options specifically for workshops. We collect all the same information from </em></strong><strong><em>the participant when they make a reservation. While participants might qualify for a discount on the </em></strong><strong><em>base-fee, as with a demonstration, there is no discount on the materials fee as we need to cover </em></strong><strong><em>that cost. So, for example, even an MHR member has to pay the full materials fee if they book a </em></strong><strong><em>workshop. The other difference is that workshop reservations are non-refundable, so the system </em></strong><strong><em>should refuse to cancel one.”</em></strong>

<strong><u>Important:</u></strong><strong> Your supervisor advises that your stage C program must utilise the same single </strong><strong><u>array</u></strong><strong> used in stage </strong><strong>B for storing information about all the demonstrations, in the class called <em>ProgMgmtSys. </em>Your supervisor </strong><strong>advises that program should be able to operate correctly on stage C cases from the <em>TestCases.pdf </em>file and the </strong><strong>menu in <em>ProgMgmtSys </em>updated as necessary for the user to choose any required new functionality. </strong><strong>Collections should not be used. You are expected to adhere to all relevant object-oriented programming </strong><strong>guidelines as described in stage <em>A.</em></strong>