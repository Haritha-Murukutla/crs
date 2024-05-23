# Crime-Reporting-System
The Online crime reporting system which is a Web application designed in PHP  which aims to provide crime management solutions such as filing of FIR  and checking its status accessible to everyone

User Portal

    Registration and Login: Users can register using their Aadhar card and log in.
    File a Complaint: Users can file a complaint, which requires Aadhar card validation.
    Nearest Police Station: Detects the user's current location and shows the nearest police station.

Police Officer Portal

    Login: Police officers can log in to their portal.
    Case Updates: Police officers can update the status of cases assigned to them (e.g., FIR filed, criminal identified, criminal caught).
    View Assigned Cases: Officers can see a list of cases assigned to them.

Station In-Charge Portal

    Login: Station in-charges can log in to their portal.
    View All Cases: View all cases assigned to officers within their station.
    Add Police Officers: Ability to add police officers to their station.

Headquarters Portal

    Login: Headquarters personnel can log in to their portal.
    Manage Police Stations: Add new police stations and assign them to different areas.
    View All Cases: View all cases across all police stations.


Functional Workflow

    User Registration and Complaint Filing
        User registers and logs in using their Aadhar card.
        User files a complaint, which is automatically assigned to a police officer at the nearest station based on the user's location.

    Case Assignment and Management
        Complaints are randomly assigned to available officers at the nearest police station.
        Police officers can log in, view, and update the status of their assigned cases.

    Station In-Charge Management
        Station in-charges can log in to view all cases within their station.
        In-charges can add police officers to their station.

    Headquarters Oversight
        Headquarters can manage police stations and assign them to specific areas.
        Headquarters can view all cases across all stations for broader oversight.