## Software Test Description: Fruity Nutrition App

### 1. Introduction:

The purpose of this software test is to verify the functionality and performance of a mobile application developed for iOS and Android platforms. The application aims to provide users with information about various fruits, allow them to select multiple items, calculate their nutritional values using the Fruityvice API, and enable sharing of results via email or social media. Additionally, the application may display a map of the closest supermarkets and send notifications when the user is within a proximity of 100 meters.

### 2. Test Objectives:

The key objectives of this test are as follows:

-   Verify that the application displays a list of at least 10 items/fruits.
-   Ensure that users can select multiple items in a cart-style interface.
-   Validate the accuracy of nutritional value calculations using the Fruityvice API.
-   Confirm that sharing results via email and social media is functional.
-   (Bonus) Test the functionality of displaying a map of the closest supermarkets.
-   (Bonus) Verify the ability of the application to send notifications when the user is within 100 meters of a location.

### 3. Test Scenarios:

#### 3.1. Displaying Items/Fruits:

**Objective:** Verify that the application displays a list of at least 10 items/fruits.

**Test Steps:**

1.  Launch the application.
2.  Navigate to the items/fruits section.
3.  Verify that a list of at least 10 items/fruits is displayed.
4.  Ensure the names of the items/fruits are correctly shown.

#### 3.2. Selecting Multiple Items in Cart Style:

**Objective:** Ensure that users can select multiple items in a cart-style interface.

**Test Steps:**

1.  Launch the application.
2.  Navigate to the items/fruits section.
3.  Select multiple items by tapping on them.
4.  Verify that the selected items are visually highlighted.
5.  Check that the selected items are added to the cart.

#### 3.3. Nutritional Value Calculation:

**Objective:** Validate the accuracy of nutritional value calculations using the Fruityvice API.

**Test Steps:**

1.  Launch the application.
2.  Select a few items from the cart.
3.  Initiate the nutritional value calculation.
4.  Verify that the application fetches the data from the Fruityvice API.
5.  Check that the calculated nutritional values align with the retrieved data.
6.  Test with different combinations of items to ensure accurate calculations.

#### 3.4. Sharing Results via Email/Social Media:

**Objective:** Confirm that sharing results via email and social media is functional.

**Test Steps:**

1.  Launch the application.
2.  Select a few items from the cart.
3.  Initiate the nutritional value calculation.
4.  Verify that the calculated results are displayed.
5.  Attempt to share the results via email and social media.
6.  Check that the sharing functionality launches the respective applications.
7.  Verify that the shared content includes the nutritional values and selected items.

#### 3.5. Displaying Map of Closest Supermarkets (Bonus):

**Objective:** Test the functionality of displaying a map of the closest supermarkets.

**Test Steps:**

1.  Launch the application.
2.  Navigate to the map section.
3.  Verify that the map is displayed.
4.  Test various locations to ensure the map shows the correct supermarkets.
5.  Confirm that the displayed supermarkets are accurate and relevant.

#### 3.6. Sending Notifications within 100m Proximity (Bonus):

**Objective:** Verify the ability of the application to send notifications when the user is within 100 meters of a location.

**Test Steps:**

1.  Launch the application.
2.  Allow the application to access the user's location.
3.  Move within the proximity of 100 meters to a location.
4.  Verify that the application sends a notification.
5.  Test with different locations to ensure the notification is triggered correctly.

### 4. Test Environment:

The test will be conducted in the following environment:

-   iOS devices (iPhone or iPad) with the latest version of iOS.
-   Android devices (phones or tablets) with the latest version of Android.
-   Test devices should have an internet connection for API access.
-   Devices with varying screen sizes and resolutions should be used for compatibility testing.

### 5. Test Deliverables:

The following deliverables will be provided as a result of the test:

-   Test report documenting the test objectives, scenarios, steps, and results.
-   Screenshots or videos showcasing the test execution, especially for UI-related tests.
-   Any bug reports or issues encountered during the testing process.

**Note:** The test scenarios provided in this document are for reference purposes only. Additional test scenarios may be derived during the test execution based on the application's behavior and requirements.enter code here
