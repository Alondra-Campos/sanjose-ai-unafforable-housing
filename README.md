# Permit Review Assistant: AI for Catching Incomplete Permit Applications Early

Client: Santa Clara County, building permit review
Team: Alondra Campos, Ivan Barrera Rivera, Belinda Flores, Luis Garcia, Alija Gacanovic, Aug–Oct 2026
My part: I led the team and built the prototype in Replit, from the pre-screening logic to the staff and applicant portals.

## The problem
County permit staff review a high volume of building applications, and they must manually sort through incomplete or inconsistent ones before real review can begin. That creates bottlenecks, slows feedback to applicants, and delays housing development.

## What we built
- An AI pre-screening tool that checks housing permit applications, flags missing information (such as a fire inspection), and stops applications outside Santa Clara County.
- Two portals. Staff see a prioritized queue with flags and conflict labels. Applicants see a simple dashboard to track their application status.
- The AI only flags issues. A County staff member verifies each claim and makes the final decision.

## What I would do next
The red-team test showed the app accepted an Oakland address, and we fixed it so it now rejects addresses outside the County. The bigger gap is governance: anyone can sign up as staff, and decisions aren't tied to a verified County employee. Next, I would design County-verified sign-in with admin-approved roles and regular decision-log review, and I would learn enough Statistics and ML to measure how accurate the flags are.
