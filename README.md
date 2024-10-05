# Project-Tracker
Project Tracker app is a project tracking application designed using Microsoft Power Apps, integrating seamlessly with SharePoint as the database for project information. This app enables teams to manage and monitor their projects effectively, ensuring efficient collaboration and communication.

---

### Key Features

- **User-Friendly Interface**: The app features a responsive and intuitive interface designed with Power Apps, ensuring a seamless experience across various devices (desktops, tablets, and smartphones).
- **Project Management**: Users can easily create, edit, and delete project entries. The app captures essential project details, including project name, start and end dates, description, status, and assigned project owner.
- **SharePoint Integration**: All project data is securely stored in a SharePoint list, which acts as a centralized database. This integration allows for easy access to real-time project information and facilitates collaboration among team members.
- **Email Notifications**: Automated email notifications are sent through Power Automate whenever new projects are added or existing projects are updated. This keeps all relevant stakeholders informed of changes in real time.
- **Real-Time Data**: The app ensures that all project information is current and accessible, enabling effective team collaboration and timely decision-making.

### Technologies Used

- **Power Apps**: Utilized for building the user interface of the app, allowing users to browse available projects, submit updates, and track their statuses efficiently.
- **SharePoint**: Serves as the backend to securely store project-related information, ensuring data integrity and easy access for users.
- **Power Automate**: Automates workflows and notifications, enhancing communication about project updates and facilitating approvals as necessary.

---

### How the ProjectTrackerApp Works

1. **User Interaction via Power Apps:**
   - Upon launching the app, users are presented with a clean and organized interface that displays existing projects.
   - Users can browse through the list of projects and click on an option to create a new project. The form captures essential details, such as:
     - **Project Name**: The title of the project.
     - **Start Date**: When the project is set to commence.
     - **End Date**: The expected completion date.
     - **Description**: A brief overview of the project’s objectives and scope.
     - **Status**: Current status (e.g., Not Started, In Progress, Completed).
     - **Owner**: The person responsible for overseeing the project.
   - After filling in the necessary fields, users submit the project for storage in the SharePoint list.

2. **Data Storage via SharePoint List:**
   - Upon submission, the project details are saved in a dedicated SharePoint list, which serves as the centralized repository for all project information.
   - The SharePoint list is structured to include the following fields:
     - **Project Name**
     - **Start Date**
     - **End Date**
     - **Description**
     - **Status** (with options to update as the project progresses)
     - **Owner** (to indicate project accountability)
   - SharePoint’s robust security measures ensure that all data is securely stored and accessible only to authorized users, facilitating both privacy and compliance.

3. **Approval Flow via Power Automate:**
   - When a new project is added to the SharePoint list, a **Power Automate** flow is automatically triggered.
   - This flow sends an email notification to relevant stakeholders, informing them of the new project and providing essential details.
   - Stakeholders can respond to the notification, facilitating communication about the project. If further approvals are required, the flow can be configured to include multiple approvers.
   - Depending on the response, the SharePoint list is updated to reflect the current status of the project, and stakeholders receive additional notifications:
     - **Approved**: The project owner receives a confirmation email, and the project status is updated accordingly.
     - **Rejected**: The project owner is notified of the rejection, along with feedback for improvement.

4. **Notifications and Status Updates:**
   - The integration with Power Automate ensures that all stakeholders, including project owners and team members, receive timely notifications about project submissions and status updates.
   - Users can view the status of their projects within the app, which enhances transparency and ensures that everyone is aligned on project progress and responsibilities.

5. **Real-Time Monitoring:**
   - The app leverages SharePoint to provide staff with real-time insights into project statuses, including completed projects, projects in progress, and any pending approvals.
   - Users can filter and sort projects based on various criteria (e.g., status, owner, dates) to quickly find relevant information.

### Preview the App in Action

To see a demo of how the **ProjectTrackerApp** works, showcasing its user interface and functionalities, watch this detailed video:

[**Watch the ProjectTrackerApp Demo**](https://drive.google.com/file/d/1qRXzbr6_AaRpqOs9DbPGg8mynllJxaBL/view?usp=drive_link)

---

### Customization

- **Additional Fields**: Users can modify the SharePoint list to include more fields (e.g., budget, priority level) for more detailed project tracking.
- **Approval Logic**: The Power Automate flow can be enhanced to include multi-level approvals or conditional logic based on project size or complexity.
- **Notification Customization**: Email templates used in notifications can be tailored to include branding elements, detailed project information, or links to relevant resources.

### Future Enhancements

- **Task Management**: Integrate task management features to break down projects into smaller, manageable tasks, allowing team members to assign responsibilities and deadlines.
- **Analytics Dashboard**: Incorporate a Power BI dashboard to visualize project data, tracking performance metrics such as project completion rates, resource utilization, and overall team productivity.
- **Multi-Language Support**: Enable language customization options to cater to users from different regions, enhancing usability for diverse teams.

### Contributing

Feel free to open a pull request if you'd like to contribute to the project. All contributions are welcome! Whether it's fixing bugs, adding features, or improving documentation, your input can help enhance the **ProjectTrackerApp** for all users.
