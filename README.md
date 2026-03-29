# Research_Prototype_Model_for_EV_in_Pakistan
Cloud-Enabled Electric Vehicle Charging and Management: A Prototype Model for Pakistan

Abstract
The increase in the adoption of electric vehicles (EV) in Pakistan has led electric vehicle owners
to face many issues. These issues include searching for the nearest charging station, long waiting in
queues at charging stations, difficulty in making payments of charging sessions and trip planning for
long drives on electric vehicles. Due to all these, electric vehicle owners in Pakistan face frustration and
become hesitant in the daily use of electric vehicles. Although there are some global EV platforms
available to address these issues, but they do not provide a solution in the context of Pakistan.
To address these issues, this study presents ChargeEase, a cloud-based prototype that allows users
to find the nearest charging station according to their location using Open Street Maps API, see
reviews of charging stations left by other users, remotely book a charging slot at station with a
simulated local gateway of payment and leave a review of charging station after charging session.
The application is developed using HTML, CSS and JavaScript for frontend and backend services like
user authentication, real-time slot booking, etc., are powered by Firebase. The mobile version of the
application is a web wrapper in Flutter using WebView to access its services. When the application
was tested by users, the results showed that users consistently accomplished simple tasks like charging
station discovery and reservation of a charging slot, while the trip planning feature faced limitations
of greedy routing strategy in sparse regions and revealed slot booking release time issues in session
lifecycle management. Quantitatively, urban areas showed a high success percentage, whereas longdistance trip plans showed a significant decrease in success and increase in stops in the route of the
trip, which indicated sensitivity to the number of charging stations available in an area. These results
show the feasibility of a localized electric vehicle charging stations ecosystem and highlight practical
implications for improvement, such the integration of a real local payment gateway, and automatic
slot-expiry mechanisms. Currently, this application only aims to show as proof-of-concept of these
discussed features and their performance with limitations.

Keywords: : Electric Vehicles, Charging Station, Digital Cloud-based Platform
