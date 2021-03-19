# Chairy_Picker
Code to help chose next chair at the Strong Gravity meetings at Perimeter Institute and incentivize interactions during the meeting.

Each person at the meeting is associated with an integer. At the end of the meeting an integer is picked from a semi Gaussian distribution, the lower the integer a person has, the more likely they are to be picked as the next chair. Each person's number changes during the meeting with the following rules:
(1) "Group Status", a member gains 2 points if the person is faculty, 1 point for post-doc, 0 for graduate student
(2) A person gains 2 points for presenting a paper or research during the meeting.
(3) A person gains 1 point for asking questions during the meeeting.
(4) A person gains 1 point per previous times they have chaired.
