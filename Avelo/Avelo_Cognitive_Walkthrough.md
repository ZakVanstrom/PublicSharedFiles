# Cognitive Walkthrough and Analysis - Aveloair.com

## Process Description
1. Generate a complete list of steps required to complete the task.
2. For each step, answer following questions, with an explanation when useful:
	1. **Will the User know the next step?**

	2. **Will the User see the control?**

	3. **Will the User understand the control?**

	4. **If the correct action is performed, will the User see that progress is made toward the solution of the task?**
3. Provide a summary of findings.

## Task Parameters

### Task Description

**Flight Selection.** Go to Aveloair.com and get tickets for an upcoming flight.

### Requirements
1. From Fort Collins/Loveland, CO to Las Vegas, NV
2. From Dec. 18th to Dec 22nd
3. Must have ‘Extra Legroom’
4. One (1) Bag: 28” x 20” x 14”

### Preferences
1. Minimize Cost
2. Priority Boarding

## Environment Details

### System

<img width="259" alt="image" src="https://user-images.githubusercontent.com/48782399/139567785-57f0eb15-8e55-45c1-b89e-9f8c62a323bc.png">

### Browser

Safari - 15.1 (17612.2.9.1.20)

### Date/Time

Oct. 29th, 2021. ~10pm EST.

### Autofill Settings

<img width="494" alt="image" src="https://user-images.githubusercontent.com/48782399/139567776-e487d011-0ecd-434b-ae71-a880f033eda2.png">

# Cognitive Walkthrough

## Search Function

<b>1. Load Home Page - aveloair.com</b>

<details>
	<summary><b>2. Type ‘Fort Collins’ in Depart Box and click the ‘Fort Collins’ Result</b></summary>
	
	1. Yes, if they know why they’re visiting site.
	2. Yes, it’s in an obvious location.
	3. Yes, if they have familiarity with search by city functions.
	4. Yes, the box will be filled.
</details>

<details>
	<summary><b>3. Type ‘Las Vegas’ in Arrive Box and click the ‘Las Vegas’ </b></summary>
	
	1. Yes.
	2. Yes.
	3. Yes.
	4. Yes.
</details>


<details>
	<summary><b>4. Select date range in Dates Box from 18th Dec to 22nd Dec and click ‘Apply’</b></summary>
	
	1. Yes, this step involved selecting a desired date range given a Round Trip, which is the preselected option.
	2. Yes, if they’re looking for the next step, they’ll see it as further down the list of prerequisites for searching.
	3. No, the act of selecting two dates can be confusing.
	4. Yes, progress is obvious as the date range is filled afterwards.
</details>

<details>
	<summary><b>5. Make sure Customers equals one adult</b></summary>
	
	1. Yes, they’ll know they need to change it if they don’t only have 1 adult flying.
	2. Yes, it’s obvious within the selections.
	3. Yes.
	4. Yes, there’ll be a change if they make a change.
</details>

<details>
	<summary><b>6. Click Search</b></summary>
	
	1. Yes. Assuming they’ve inspected the entire search box, they should realize that they should click search to send the query. Noting no new options become available.
	2. Yes.
	3. Not necessarily, see #1.
	4. Yes.
</details>

## Flight Selection

<details>
	<summary><b>1. Click the Toggle Button for desired departing flight</b></summary>
	
	1. Yes, but only after reading through other information on page. Not obvious.
	2. No, the control is a section of the screen surrounding a toggle circle, but becomes obvious if you hover over that area.
	3. Yes, it just requires a single click in that area.
	4. Yes, after click the UI makes the completion of that step obvious.
</details>

<details>
	<summary><b>2. Click the Toggle Button for desired returning flight</b></summary>
	
	1. No, as the previous step doesn’t indicate what the following step will be.
	2. No, but they’ll have learned from the previous step.
	3. Yes.
	4. No, after this step the screen automatically goes ahead, without acknowledging that progress was made.
</details>

<details>
	<summary><b>3. Enter personal information into forum</b></summary>
	
	1. Yes, it’s a typical forum confirming information.
	2. Yes.
	3. Yes.
	4. Yes.
</details>

<details>
	<summary><b>4. Click 'Next' Button </b></summary>
	
	1. Yes, once they’ve entered all their information, next make sense.
	2. Yes.
	3. Yes.
	4. Yes.	
</details>

## Seat Selection

<details>
	<summary><b>1. Select Seat Button for Depart</b></summary>
	
	1. Yes, if they slow down to read.
	2. Yes.
	3. No, the button isn’t specific it only says “Select Seat,” without specifying what it’s for.
	4. Yes.
</details>

<details>
	<summary><b>2. Select Box for Extra Leg Room</b></summary>
	
	1. Yes, if they slow down enough to understand diagram.
	2. Yes, all options are very visible.
	3. No, it isn’t obvious what’ll happen when clicking a control. After clicking, browser loads to top in ‘hard-to-get-back’ way.
	4. Yes.
</details>

<details>
	<summary><b>3. Click 'Close' Button</b></summary>
	
	1. No, they have to assume based on what they see.
	2. Yes.
	3. No, the button for ‘Close’ doesn’t clearly indicate if the seat selection process is over.
	4. Yes, there is visible progress, but that progress isn’t explained.	
</details>

<details>
	<summary><b>4. Repeat process for Returning flight</b></summary>
	
	1. No, a passenger may assume they have selected their option for both flights. It is not clear they need to do so for their return flight as well.
	2. Yes.
	3. Yes.
	4. Yes.	
</details>

## Bag Selection

<details>
	<summary><b>1. Select ‘Review Selections’ Button for Checked Bag</b></summary>
	
	1. No, the customer has to confirm the size of their bag and read the details to know if they can bring a carry-on, or if they have to do a checked bag.
	2. Yes.
	3. No, ‘Review Selections’ implies that there are default selections, when there aren’t.
	4. No, the drop-down doesn’t really seem like proper progress.
</details>

<details>
	<summary><b>2. Select Yes for First Bag on Depart</b></summary>
	
	1. No, there’s several toggle boxes that need reading before selection.
	2. No, the control isn’t obvious.
	3. No, not until they look closely at the ‘yes’ and ‘no’ options.
	4. No, not in a meaningful way.
</details>

<details>
	<summary><b>3. Select Yes for Second Bag on Arrive</b></summary>
	
	1. No.
	2. No.
	3. No.
	4. No.
</details>

<details>
	<summary><b>4. Click Confirm Selections (Unnecessary)</b></summary>
	
	1. No, it isn’t obvious.
	2. No, they have to go back up to see it.
	3. Yes, the button ‘Confirm Selections’ makes sense.
	4. No, the drop-down just shrinks. Under closer inspection, they’ll find the bag included on summary on right.
</details>

## Priority Boarding Selection

<details>
	<summary><b>1. Click Priority Boarding: Review Selection Button</b></summary>
	
	1. Yes, as it’s next in line vertically.
	2. Yes, button is visible.
	3. No, reviewing selections doesn’t make sense when a selection hasn’t been made.
	4. Yes, dropdown opens.
</details>

<details>
	<summary><b>2. Click Yes Toggle Box for Depart</b></summary>
	
	1. Yes.
	2. No, it’s just toggle boxes that don’t have an indication that makes them look like controls.
	3. No, It’s not obvious what that part of the screen will do.
	4. No, just a toggle box switched, except under closer inspection
</details>

<details>
	<summary><b>3. Click Yes Toggle Box for Return</b></summary>
	
	1. Yes.
	2. No.
	3. No.
	4. No.
</details>

<details>
	<summary><b>4. Click Confirm Selections (Unnecessary)</b></summary>
	
	1. No.
	2. No.
	3. Yes.
	4. No.
</details>

## Confirmation

<details>
	<summary><b>1. Click ‘Next’ Button</b></summary>
	
	1. No, they still need to review to figure out what the site’s defaults were.
	2. Yes, it’s obvious and visible.
	3. Yes, the site will pretty obviously move forward if next is pressed.
	4. Yes, as it goes to the next page.
</details>

<details>
	<summary><b>2. Review Terms and Conditions</b></summary>
	
	1. No, the User isn’t told to read the terms.
	2. No, it’s hard to view the terms.
	3. No, it’s hard to figure out what’s going on.
	4. No, it doesn’t feel like it matters to read them.
</details>

<details>
	<summary><b>3. Click toggle box for Agree</b></summary>
	
	1. Yes.
	2. Yes.
	3. No, it doesn’t seem like enough to confirm agreement.
	4. No, a toggle-box just toggles it and doesn’t make the ‘Next’ button seem more available than before.
</details>

<details>
	<summary><b>4. Click 'Next' Button</b></summary>
	
	1. No, this control is available at the load of the page, but isn’t available initially, so it’s hard to know when it’ll be available.
	2. Yes, it’s easily visible.
	3. Yes, the control makes sense.
	4. Yes, pressing ‘Next’ loads the next section.
</details>

## Payment Information

<details>
	<summary><b>1. Enter payment information into Forum</b></summary>
	
	1. Yes. Strong similarity to other payment sites.
	2. Yes.
	3. Yes.
	4. No, as the entering of information does not cause anything to be highlighted. However, the bar near top of screen displays progress. Something only noticed here the process.
</details>

<details>
	<summary><b>2. Click ‘Purchase’ Button</b></summary>
	
	1. Yes, they’ll click Purchase after they’ve confirmed their details.
	2. Yes, it’s the brightest button on the page, located on right side where it’s placed naturally.
	3. Yes, assuming button finishes entire transaction. Untested.
	4. Yes, assuming above. Untested.
</details>

## Bugs & Minor Flaws Found during Walkthrough

1. After some time away from ‘Terms and Conditions’ page, an Error shows “Session expired, please reload page”. 
	1. Reloading page doesn’t resolve error.
	2. Going to previous page doesn’t resolve error.
	3. Going back to home page resolves error, but *loses all flight selection progress*
2. Safari’s Password Manager automatically inserts ‘Debit / Credit Card Number’ and ‘Expiration Date’, but fails to complete ‘Name (As On Card)’
3. Making a change in the ‘Seat Selection’ menu causes the browser to load from the top, resulting in the User losing their place.


# Walkthrough Summary
Aveloair.com’s interface is bright and simple, yet has some steps that felt out-of-place. Shared below are conclusions based from the above Cognitive Walkthrough, judged with the following design principles in mind:

1. Keep the User in Control
2. Maintain Familiarity and Comfort
3. Reduce Cognitive Load
4. Maintain UI Consistency

## Step Summaries

### Search for Flight

The search functionality on *aveloair.com**’s* homepage feels well-implemented. It mimics the same flow as many other sites, while reducing clutter. 

<details>
	<summary>1. Additional options within the ‘Search Box’ caused the User to go off-track, like the ‘Low-Fare Calendar’ Toggle-Box. It causes the search to return a calendar instead of searched results, where a User likely wanted to search, not only view that calendar. That option has little information visible, so it’s a halting point in a Users’ decision to search and increases cognitive load.</summary>
	
	Including a ‘Hover-Over’ information for the ‘Low-Fare Calendar’ Toggle-Box would help a User know if it’s worth toggling that option.
</details>

<details>
	<summary>2. The Search Box does not display when it is ready to search. </summary>
	
	Highlighting the Search Box when ready to search would help a User know when it’s time to search.	
</details>

### Flight Selection


<details>
	<summary>1. The Toggle Options create confusion. They’re placed with suboptimal distancing that makes the selection of ‘Yes’ or ‘No’ challenging. Further, their options aren’t separated or  displayed as a Button.</summary>
	
	Turning the Toggle Options into Buttons would help the User see them quickly.
</details>

2. The continuation from ‘Selecting a Flight’ to the next page happens without confirmation, causing confusion and an out-of-control feeling. Turning those options into more obvious Buttons would be helpful.

<details>
	<summary>3. The chart displayed has multiple ‘Unavailable’ type options, which are still available as buttons.</summary>
	
	By disabling those buttons, a User wouldn’t be distracted into thinking they’re an available option.
</details>


### Seat Selection
1. Seat Selection is placed in a list of additional options, which forces the User to make a choice as to which requirement they want to fill next. 
2. If they want ‘Extra-Legroom,’ this is the first opportunity a User has to make that preference (It wasn’t available in the search screen).

### Bag Selection
1. ‘Review Selections’ implies to Users that selections have already been made.
2. Clicking ‘Confirm Selections’ only reduces the drop-down. The responsive flight-basket feels great as a User, but Confirm Details doesn’t *do *anything.

### Priority Boarding Selection 

1. The Toggle Boxes feel more intuitive here, but still lack separation and buttony-ness.
2. ‘Confirm Selections’ maintains consistency here, but still feels out of place as a User.

### Confirmation

<details>
	<summary>1. Reviewing the Terms and Conditions is available as a link, but isn’t automatically displayed to the User.</summary>
	
	Some Users may feel more comfortable if the T&C’s are displayed automatically, but don’t require scrolling before hitting ‘Agree’.
</details>

<details>
	<summary>2. Next doesn’t change when the ‘Agree’ toggle box is changed</summary>
	
	Some Users feel more comfortable when the ‘Next’ Button is highlighted after the ‘Agree’ requirement is completed.
</details>

### Payment Information

1. The payment information box feels standard, rather than continuous with previous UI.
2. Payment information is clear, but the final ‘Purchase’ Button doesn’t confirm if its the final step or if there’s a review point coming up.


## Final Note

Thank you engaging with and reviewing this cognitive walkthrough. I sincerely hope it can provide some insight on your User Experience from an external perspective.

Regards,

**Zak Vanstrom**

Honors Computer Science, ASU 2022
