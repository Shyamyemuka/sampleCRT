
# CodeHub — Complete Feature Breakdown

---

## 🌐 MAIN PAGE (Public Website — Visible to Everyone)

This is your showcase page, like any company/organization website. No login required to view.

### **1. Navigation Bar (Sticky Header)**
- CodeHub Logo + Name
- Home
- About Us
- Our Team
- Events
- Competitions
- Leaderboard
- Gallery
- Contact Us
- **Sign In / Register** button (top-right)
- *(After login:* **"My Dashboard"** button replaces Sign In)*

---

### **2. Hero Section (Landing Banner)**
- Catchy tagline (e.g., *"Code. Compete. Conquer."*)
- Animated background or code-themed visuals
- CTA buttons: **"Join CodeHub"** (registration) & **"Explore Events"**
- Member count ticker / stats (e.g., "50+ Members | 10+ Events | 5 Competitions")

---

### **3. About Us Section**
- What is CodeHub (mission, vision, purpose)
- What the club does (debugging competitions, tech auctions, coding workshops, etc.)
- Brief history / when it was founded
- Club's objectives & values
- Faculty Advisor / HoD mention (if applicable)

---

### **4. Our Team Section** *(Treasurer role REMOVED)*
| Role | Members |
|------|---------|
| **President** | Shyam Yemuka (23701A3280) |
| **Vice-President** | Jagadeeshwar C V (23701A30D9) |
| **Secretary** | Sowmya O (23701A3281), Vyshnavi S (23701A30F1) |
| **Tech Lead** | Santosh D (23701A3B5), Rakesh Kumar Reddy A (24705A3016) |
| **Asst. Tech Lead** | Sreelekha B (23701A3285), Sri Harsha K (23701A3287) |
| **Event Coordinator** | Vishnu Vardhan Reddy A C (23701A30E8), Lakshmi Priya M (24705A3007), Venkata Jayasree K (23701A32A0) |
| **Design & Media Lead** | Reddy Vishnu Vardhan V (2371A30A3), Venkata Ravi Teja M (23701A30E1) |
| **Asst. Design & Media Lead** | Harini P (24AFCSD031), Divya Teja K (24AFCSD023) |
| **Logistics & Outreach** | Vardhan Kumar Reddy R (24705A3024), Kasturi L (24AFCSD052) |

- Each card: Photo, Name, Roll No., Role, LinkedIn/GitHub links (optional)

---

### **5. Events Section**
- **Upcoming Events** — cards with event name, date, time, venue, short description, "Register Now" button
- **Past Events** — archive with summary, photos, results link
- Event category tags (Workshop, Competition, Hackathon, Tech Auction, etc.)

---

### **6. Competitions Section**
- List of all debugging competitions (upcoming & past)
- For each competition:
  - Name, Date, Description, Rules
  - Status badge: *Upcoming / Live / Completed*
  - "Register" button (for upcoming)
  - "View Results / Leaderboard" link (for completed)

---

### **7. Leaderboard Section (Public View)**
- **Competition-wise Leaderboard** — dropdown/tab to select a specific competition → shows rank, name, score, time
- **Overall Leaderboard** — aggregated scores across ALL competitions conducted so far
- Columns: Rank, Participant Name, Roll No., Total Score, Competitions Participated, Best Rank
- Top 3 highlighted with gold/silver/bronze badges
- Search & filter options

---

### **8. Tech Team Auction Section**
- Explanation of the IPL-style auction concept
- How it works (leads are selected → teams are auctioned — tech team, presentation team, etc.)
- **Upcoming Auction** — date, time, rules, eligible participants
- **Past Auction Results** — which leads picked which members, team compositions
- Live auction page (if you want to do it live on the website — optional/future)

---

### **9. Gallery Section**
- Photos & videos from past events, competitions, team activities
- Organized by event/date

---

### **10. Registration / Sign Up Section**
- **New Student Registration Form:**
  - Full Name
  - Roll Number
  - Email (college email preferred)
  - Phone Number
  - Branch / Department
  - Year of Study
  - Areas of Interest (checkboxes: Web Dev, DSA, AI/ML, Competitive Coding, etc.)
  - Password & Confirm Password
  - *(Default role assigned: Student)*

---

### **11. Sign In Section**
- Roll Number / Email + Password login
- Forgot Password option
- After login → "My Dashboard" button appears in nav bar

---

### **12. Contact Us / Footer**
- Club email address
- Social media links (Instagram, LinkedIn, GitHub, etc.)
- College name & address
- Quick links to all sections
- "© 2025 CodeHub — All Rights Reserved"

---

---

## 🎓 STUDENT / PARTICIPANT DASHBOARD

*(Opens when a user with "Student" role clicks "My Dashboard")*

### **1. Welcome / Overview Panel**
- "Welcome, [Student Name]!" with profile picture
- Quick stats:
  - Competitions Participated: X
  - Overall Rank: #Y
  - Total Score: Z
  - Upcoming Events: N

---

### **2. My Profile**
- View & Edit:
  - Name, Roll No., Email, Phone, Branch, Year
  - Profile Picture upload
  - Areas of Interest
  - Change Password
- **NO option to request admin access** *(as per your requirement)*

---

### **3. Upcoming Events**
- List of upcoming events/competitions with:
  - Event Name, Date, Time, Venue, Description
  - **"Register"** button (if registration is open)
  - Registration status: *Registered / Not Registered / Registration Closed*

---

### **4. My Registrations**
- List of all events/competitions the student has registered for
- Status: *Upcoming / Ongoing / Completed*
- Option to **withdraw** from upcoming events (before deadline)

---

### **5. My Competition Results**
- Table/list of all competitions participated in:
  - Competition Name, Date, Score, Rank, Status (Completed/Ongoing)
- Click on a competition → detailed result & leaderboard for that competition

---

### **6. Leaderboard View**
- **Competition-wise Leaderboard** — select competition from dropdown → see full ranking
- **Overall Leaderboard** — cumulative across all competitions
- Student's own position highlighted

---

### **7. Tech Team Auction**
- **My Auction Status:**
  - Whether the student is in the auction pool
  - Which team they were picked for (after auction)
  - Team Lead name
  - Team Members list
- View past auction results

---

### **8. Announcements / Notifications**
- Club announcements from admins
- Event reminders
- Competition result announcements
- Notification bell icon with unread count

---

### **9. Resources (Optional but Recommended)**
- Study materials, coding practice links, past competition problems
- Shared by admins/tech leads

---

### **10. Logout**

---

---

## 🛡️ ADMIN DASHBOARD

*(Opens when a user with "Admin" role clicks "My Dashboard")*
*Initial admins: President (Shyam), Vice-President (Jagadeeshwar), Tech Lead (Santosh & Rakesh). They can grant admin to others.*

### **1. Admin Overview / Home Panel**
- Welcome message with admin name & role
- Quick stats dashboard:
  - Total Registered Members
  - Active Competitions
  - Upcoming Events count
  - Recent Registrations
  - Total Competitions Conducted
- Recent activity feed (new signups, registrations, etc.)

---

### **2. Member Management**
- **View All Members** — searchable, filterable table:
  - Name, Roll No., Email, Branch, Year, Role (Admin/Student), Date Joined
- **Grant Admin Access** — select any student → promote to Admin
- **Revoke Admin Access** — demote an admin back to Student
- **Remove Member** — remove a member from the club
- **View Member Profile** — see individual details, competition history, scores
- Export member list (CSV/Excel — optional)

---

### **3. Event Management**
- **Create New Event:**
  - Event Name, Description, Date & Time, Venue, Event Type (Competition/Workshop/Hackathon/Auction/Other)
  - Registration deadline
  - Max participants (optional)
  - Upload banner/poster image
  - Publish / Save as Draft
- **Edit / Delete Existing Events**
- **View Registrations for Each Event** — list of registered participants
- **Mark Event as Completed**
- **Send Event Notifications/Reminders** to all members or registered participants

---

### **4. Competition Management**
- **Create New Competition:**
  - Competition Name, Description, Rules, Date & Time
  - Type: Debugging / Coding Challenge / Hackathon / etc.
  - Scoring criteria
  - Registration toggle (Open/Closed)
- **Manage Ongoing Competitions:**
  - View registered participants
  - Input/Upload Scores & Rankings (manually or via CSV)
  - Mark as Completed
- **View Past Competitions** — edit results if needed

---

### **5. Leaderboard Management**
- **Competition-wise Leaderboard:**
  - Select competition → view/edit scores and ranks
  - Add/modify participant scores
  - Auto-rank based on scores
- **Overall Leaderboard:**
  - Auto-generated from all competition scores
  - Option to configure scoring weights (optional)
  - Reset or recalculate
- **Publish / Unpublish** leaderboard (control when it becomes publicly visible)

---

### **6. Tech Team Auction Management**
- **Setup New Auction:**
  - Auction Name, Date & Time
  - Define roles/categories to be auctioned (Tech Team, Presentation Team, Design Team, etc.)
  - Select Team Leads / Captains
  - Set base price / budget per lead (virtual currency, like IPL)
  - Add participants to the auction pool
- **Conduct Auction:**
  - Live auction interface (optional — mark bids, assign members to leads)
  - Or manually assign results post-auction
- **View / Edit Auction Results:**
  - Team compositions
  - Which lead picked whom, at what price
- **Publish Auction Results** to main page

---

### **7. Announcements & Notifications**
- **Create Announcement:**
  - Title, Message, Target (All Members / Specific Event Participants / Admins Only)
  - Schedule or publish immediately
- **View Past Announcements** — edit/delete
- **Push Notifications** to student dashboards

---

### **8. Registration Management**
- **View All New Sign-ups** — approve or review
- **Registration Analytics:**
  - Total signups, signups per event, branch-wise distribution, year-wise distribution
- **Export Registration Data**

---

### **9. Content Management (Main Page)**
- **Edit About Us** section content
- **Update Team Details** — add/remove/edit team members and roles
- **Manage Gallery** — upload/delete photos and videos
- **Edit Contact Information & Social Media Links**
- **Update Hero Section** banner/tagline

---

### **10. Admin Profile**
- View & Edit own profile
- Change Password
- View admin activity log (optional)

---

### **11. Logout**

---

---

## Summary Table

| Feature | Main Page | Student Dashboard | Admin Dashboard |
|---|---|---|---|
| About / Club Info | ✅ View | ❌ | ✅ Edit |
| Team Members | ✅ View | ❌ | ✅ Manage |
| Events | ✅ View | ✅ View + Register | ✅ Create/Edit/Delete |
| Competitions | ✅ View | ✅ View + Register | ✅ Create/Manage/Score |
| Leaderboard (Per Competition) | ✅ View | ✅ View (self highlighted) | ✅ View + Edit Scores |
| Overall Leaderboard | ✅ View | ✅ View (self highlighted) | ✅ View + Manage |
| Tech Team Auction | ✅ View Info + Results | ✅ View own team/status | ✅ Full Setup & Management |
| Registration | ✅ Sign Up Form | ❌ (already registered) | ✅ View/Manage Registrations |
| Sign In | ✅ | ❌ (already signed in) | ❌ (already signed in) |
| My Profile | ❌ | ✅ View + Edit | ✅ View + Edit |
| My Results | ❌ | ✅ View | ❌ (see all via competition mgmt) |
| Member Management | ❌ | ❌ | ✅ Full CRUD + Role Assignment |
| Grant/Revoke Admin | ❌ | ❌ **No request option** | ✅ Grant/Revoke |
| Announcements | ❌ (or ticker on main page) | ✅ Receive/View | ✅ Create/Edit/Delete |
| Gallery | ✅ View | ❌ | ✅ Upload/Manage |
| Contact / Social Links | ✅ View | ❌ | ✅ Edit |

---

This gives you a complete, scalable blueprint for CodeHub's webpage, student dashboard, and admin dashboard. Want me to now proceed with the actual code/tech stack recommendations or wireframes?