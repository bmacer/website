Old menu layout:
 - [Mentor](https://www.outreachy.org/mentor/)
 - [Sponsor](https://www.outreachy.org/sponsor/)
 - [Contact](https://www.outreachy.org/contact/)
 - [Apply](https://www.outreachy.org/apply/)
 - [Promote](https://www.outreachy.org/promote/)
 - [Alums](https://www.outreachy.org/alums/)
 - [Opportunities](https://www.outreachy.org/opportunities/)

New menu layout:
- Participate
  - Apply
  - Alums
  - Opportunities
- Support
  - Mentor
  - Sponsor (goes to corporate sponsorship page)
  - Donate (goes to individual donation page)
  - Promote
- Blog
- Contact

Pages:
 - [Mentor](https://www.outreachy.org/mentor/)
   - wagtail page
 - [Mentor FAQ](https://www.outreachy.org/mentor/mentor-faq/)
   - wagtail page
 - [Sponsor](https://www.outreachy.org/sponsor/)
   - wagtail page
 - [Donate](https://www.outreachy.org/sponsor/donate/)
   - wagtail page
 - [Contact](https://www.outreachy.org/contact/)
   - wagtail page
 - [Apply](https://www.outreachy.org/apply/)
   - wagtail page
 - [Is Google Summer of Code Right for You?](https://www.outreachy.org/apply/gsoc/)
   - wagtail page
 - [Eligibility](https://www.outreachy.org/apply/eligibility/)
   - wagtail page
 - [Initial Application](https://www.outreachy.org/apply/initial-application/)
   - wagtail page
 - [Make Contributions](https://www.outreachy.org/apply/make-contributions/)
   - wagtail page
 - [Project Selection](https://www.outreachy.org/apply/project-selection/)
   - Django page
 - [Rounds](https://www.outreachy.org/apply/rounds/)
   - template - `home/templates/home/rounds_index_page.html`
 - [Promote](https://www.outreachy.org/promote/)
   - wagtail page
 - [Alums](https://www.outreachy.org/alums/)
   - wagtail page
 - [Opportunities](https://www.outreachy.org/opportunities/)
   - wagtail page
 - [Blog](https://www.outreachy.org/blog/)
   - wagtail page
   - could easily become a Django page? Search for wagtail pages with the URL base of `blog/` and sort by date and display?
 - [Outreachy Statistics for December to March 2017 Applicants](https://www.outreachy.org/blog/outreachy-statistics-december-march-2017-applicants/)
   - Django page?


Deleted or defunct pages:
 - [Application text](https://www.outreachy.org/apply/application-text/)
   - wagtail page
   - probably defunct?
   - we should be able to generate a Django page with all the possible questions a person might answer
   - deleted
 - [Finalize Your Application](https://www.outreachy.org/apply/finalize-your-application/)
   - wagtail page
   - probably defunct?
   - deleted
 - [Landing Page Requirements](https://www.outreachy.org/mentor/landing-page-requirements/)
   - need to remove references to the landing page on mentor-faq, apply, finalize-your-application pages - we now submit communities and projects, not create landing pages
   - defunct now, but we need to add the language tips somewhere:
     - Don't use the term "student" for Outreachy participants. Outreachy is open to anyone over 18 who meets our eligibility requirements, and while we often get students participating, we also get people who are in the middle of switching careers. Use "newcomer", "person/people", "applicant", "participant", or "intern" instead.
     - Please avoid using gender-specific language in your page. Outreachy is open internationally to cis and trans women, but it is also open to trans men, gender queer folks (who often have varied pronouns), and men of color in the United States. We try to make our language as inclusive as possible to avoid erasing anyone's contribution to the program. If you want to talk about how you want to increase diversity in your community, a good description is "people traditionally underrepresented in tech" with a link to our eligibility requirements. Please use "they/them" pronouns where ever possible (and yes, they can be both singular and plural).
     - Don't use "Summer" and "Winter" to designate the rounds. Since Outreachy is open internationally, "summer" and "winter" are different times of the year in different hemispheres. Use "May" and "December".
 - [Community FAQ](https://www.outreachy.org/mentor/community-faq/)
   - wagtail page
   - This was set to draft status - we can probably delete it
   - this is largely defunct now that we have the CFP pages in place
   - dropped sentence "All work done by Outreachy interns should be public and done out in the open on public channels connected with the project."
   - Do we need to talk about the mentor mailing lists on the dashboard? "Add the mentor to the outreachy-list and outreachy-announcement-list. outreachy-list is a private list for organizations' coordinators and mentors where prospective applicants can send their inquiries and applications. outreachy-announcement-list, is a low traffic list with important coordination e-mails. While the main list can get busy at times and you are only asked to follow up on e-mails reflecting interest in your organization in the subject, we ask you to keep a close eye on the e-mails sent to the announce list."