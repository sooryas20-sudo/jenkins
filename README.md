---

# Jenkins User & Project Management - Task 3

This task explores the implementation of Role-Based Access Control (RBAC), user isolation, and multi-project workspace tracking inside a live Jenkins environment.

## 👥 Implementation Details
1. **Administrative Setup:** Created a secondary non-root execution space to mimic a real-world enterprise development team environment.
2. **User Provisioning:** Successfully provisioned a new restricted user account under the profile name **`Developer1`**.
3. **Multi-Project Matrix:** Deployed 2 distinct standalone freestyle automation projects from the administrative dashboard.
4. **Access Control Validation:** Authenticated cleanly as `Developer1`, verifying that global read permissions and the two target projects map seamlessly to the new user's dashboard view.
