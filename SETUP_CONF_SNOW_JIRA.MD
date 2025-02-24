## Set up instructions for Confluence, JIRA and ServiceNow trial accounts. 

---

## Legal Disclaimer

> **⚠️ IMPORTANT:** Confluence, Jira, and ServiceNow mentioned in this documentation are third-party systems and trademarks of their respective owners. Their functionality, availability, and configurations are outside the purview of Amazon Q Business. 

*Please note:*
- Confluence® and Jira® are registered trademarks of Atlassian Corporation Plc.
- ServiceNow® is a registered trademark of ServiceNow, Inc.
- The integration capabilities described here are subject to the terms, conditions, and policies of these third-party services
- Support for these third-party systems should be obtained directly from their respective vendors
- Amazon Q Business provides integration capabilities but does not manage, control, or guarantee the functionality of these external systems


## Setting Up a Confluence Cloud Trial Account

### Prerequisites
- A valid business email address
- Internet access
- Credit card (for verification, but won't be charged during trial)

### Step-by-Step Instructions

1. **Start Trial Registration**
   - Visit the Atlassian website
   - Click "Try Free" for Confluence Cloud
   - Select "Confluence" from the available products

2. **Create Your Account**
   - Enter your business email address
   - Choose a site name (this will be part of your Confluence URL)
   - Select your region/data residency
   - Create a secure password

3. **Configure Your Site**
   - Choose "Confluence" as your primary product
   - Select team size (for trial purposes, you can start with a small team)
   - Choose "Free trial" option

4. **Complete Account Setup**
   - Verify your email address
   - Set up your profile information
   - Accept terms of service

5. **Initial Configuration**
   - Create your first space (e.g., "Team Documentation")
   - Add a test page to verify functionality
   - Note down your Confluence Cloud domain URL (you'll need this for Amazon Q setup)



> **💡 Pro tip:** Create some sample content in your space before connecting to Amazon Q to test the integration effectively.

### Required Information for Amazon Q Integration
Make note of the following details as you'll need them for Amazon Q setup:
- Your Confluence Cloud domain URL
- Admin account credentials
- Space permissions and access settings

> **⚠️ Note:** Ensure you have administrator privileges in your Confluence instance to set up the integration with Amazon Q Business.

---

---
## Setting Up a Jira Cloud Trial Account

### Prerequisites
- A valid business email address
- Internet access
- Credit card (for verification, but won't be charged during trial)

### Step-by-Step Instructions

1. **Start Trial Registration**
   - Visit the Atlassian website
   - Click "Try Free" for Jira Software Cloud
   - Select "Jira Software" from the available products

2. **Create Your Account**
   - Enter your business email address
   - Choose a site name (this will be your Jira URL: `sitename.atlassian.net`)
   - Select your region/data residency
   - Create a secure password

3. **Configure Your Site**
   - Choose "Jira Software" as your primary product
   - Select team size (for trial purposes, you can start with a small team)
   - Choose "Free trial" option

4. **Project Setup**
   - Select a project type (e.g., Scrum, Kanban)
   - Name your first project
   - Note down the project key (you'll need this for Amazon Q setup)

5. **Security Configuration**
   - Create an API token:
     1. Go to Account Settings
     2. Select "Security"
     3. Click "Create API token"
     4. Name your token (e.g., "Amazon Q Integration")
     5. Copy and securely store the API token



> **💡 Pro tip:** Create a test project with sample issues before connecting to Amazon Q to verify the integration works as expected.

### Required Information for Amazon Q Integration
Make note of the following details as you'll need them for Amazon Q setup:
- Your Jira Cloud URL (`https://your-site.atlassian.net`)
- Admin account email address
- API token
- Project key(s)

### Recommended Project Setup
1. **Create Test Issues**
   - Create at least one issue in each priority level
   - Add descriptions and comments
   - Assign to different users
   - Add attachments (if needed)

2. **Configure Basic Workflows**
   - Set up basic workflow states (To Do, In Progress, Done)
   - Create a few custom fields
   - Set up a basic board

> **⚠️ Note:** Ensure you have administrator privileges in your Jira instance to set up the integration with Amazon Q Business.

### Permissions Check
Before proceeding with Amazon Q integration, verify:
- You have admin access to the Jira instance
- API access is enabled
- Your account can create and modify issues
- You can access project settings

---

---
## Setting Up a ServiceNow Trial Account

### Prerequisites
- A valid business email address
- Internet access
- Professional/business domain email (free email providers like Gmail/Yahoo may not be accepted)

### Step-by-Step Instructions

1. **Register for Developer Instance**
   - Visit the ServiceNow Developer website
   - Click "Register" to create a ServiceNow developer account
   - Complete the registration form with your business email
   - Verify your email address

2. **Request Developer Instance**
   - Log into your developer account
   - Request a personal developer instance
   - Select the latest ServiceNow release version (We used Vancouver for the demo)
   - Wait for instance provisioning (typically takes 10-20 minutes)

3. **Initial Instance Setup**
   - Note your instance URL (format: `https://[your-instance].service-now.com`)
   - Save your admin credentials securely
   - Complete the initial setup wizard if presented


   
4. **Basic Authentication:**
   - Create a dedicated service account
   - Assign necessary roles (minimum: `knowledge_admin` and `incident_manager`)
   - Save credentials securely

  

5. **Knowledge Base Setup**
   - Navigate to Knowledge Management
   - Create a test knowledge base
   - Add several test articles
   - Set appropriate access controls

> **💡 Pro tip:** Create various types of knowledge articles with different access levels to test the integration thoroughly.

### Required Information for Amazon Q Integration
Make note of the following:
- ServiceNow instance URL
- Authentication credentials (based on chosen method)
- Knowledge base details
- Instance version (e.g., Vancouver)

### Recommended Initial Content
1. **Create Test Knowledge Articles**
   - Create articles in different categories
   - Include various content types (text, lists, tables)
   - Add attachments if needed
   - Set different access levels

2. **Configure Access Controls**
   - Set up knowledge base permissions
   - Create test user groups
   - Assign varying access levels

> **⚠️ Note:** Your ServiceNow instance will hibernate after a period of inactivity. Make sure to keep it active during the Amazon Q integration process.

### Pre-Integration Checklist
Verify the following before proceeding with Amazon Q setup:
- Instance is active and accessible
- Authentication credentials are working
- Knowledge base contains test articles
- Proper roles and permissions are configured
- Access controls are properly set up

### Important Notes
- Developer instances are for testing/development only
- Instances may reset periodically
- For production use, you'll need a paid ServiceNow license
- Keep your instance active to prevent hibernation

---
