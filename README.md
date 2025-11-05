## **Mobile-Responsive EdTech Platform developed using the MERN Stack, designed to support students, instructors, and admins.**

## **Key Features**

### Dynamic Homepage

- Fully responsive Navbar for mobile and desktop views

- Engaging code animation effects

- Tab-based switching in the "Explore More" section

- Review & Rating Slider showcasing feedback from enrolled students

- About and Contact Us pages with a working Contact Form

### User Profile Management

- Upload and update profile pictures

- Edit About Me section

- Password Reset (works locally; note: direct route access/reload isn’t supported on Vercel/Netlify)

#### Account Deletion System:

- A cron job runs daily at 1 AM

- Deletes accounts inactive for 3 days

- Logging in before 3 days automatically cancels the deletion

### Admin Dashboard

- Admin accounts can be created via backend (Postman)

- Secure Admin Login Access

- Ability to create Course Categories for the Catalog Navbar

- Categories appear only when at least one published course exists

### Instructor Portal

- Instructor sign-up with email OTP verification and login

- Create and manage courses under available categories

- Add Sections and Subsections (Video Lectures) to each course

- Publish/Unpublish courses (only published ones appear on the View Courses page)

- Edit or delete existing courses anytime

### Student Portal

- Student sign-up with OTP verification and login

- Add multiple courses to cart or use Buy Now directly

- Purchase courses via Razorpay Test Payment Gateway

- Access purchased course content with:

   - Accordion-based course structure (sections & subsections)

   - Mark videos as completed (highlighted in accordion)

   - Navigate seamlessly between videos using Previous/Next controls

### Course Engagement

- Students can submit reviews and star ratings for purchased courses

- Average ratings displayed publicly on the homepage

### View Courses Section

- Auto-sliding course carousels (pause on hover)

- Displays ratings, student count, and frequently bought courses

- Option to Add to Cart or Buy Now directly

### Dashboards

- #### Student Dashboard:

   - View all purchased/enrolled courses

   - Track learning progress and total course duration

#### Instructor Dashboard:

- Interactive Pie Chart showing student count per course

- Visual insights for total and per-course earnings

- Manage all courses efficiently from one dashboard

### About & Contact Sections

- Informative About Page detailing the platform’s purpose

- Functional Contact Us Page with a responsive inquiry form