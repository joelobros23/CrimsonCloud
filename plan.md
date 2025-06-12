# Project Plan: CrimsonCloud

**Description:** A simple web hosting platform that allows users to manage their domains, built with Ruby on Rails, Tailwind CSS, and Devise.


## Development Goals

- [ ] Configure the tailwindcss-rails gem and set up basic styling in application.tailwind.css.
- [ ] Add model validations for the Domain model to ensure name, plan, and status are present and that the name is unique per user.
- [ ] Customize the domains scaffold views (index.html.erb, _form.html.erb, show.html.erb) to utilize Tailwind CSS classes for improved UI and responsiveness.
- [ ] Modify the Domains controller to associate newly created domains with the currently logged-in user.
- [ ] In the Domains controller, ensure that users can only view, edit, and delete domains that belong to them.  Implement authorization logic.
- [ ] Add a dashboard page showing the user's registered domains and other relevant information.
- [ ] Implement different hosting 'plans' with varying resource limits (e.g., storage, bandwidth).
- [ ] Add a payment gateway integration (Stripe or similar) to allow users to purchase and manage subscriptions. This is a stretch goal and would require additional gems and a paid Stripe account.
- [ ] Include a basic 'status' field for each domain (e.g., active, pending, suspended) and allow administrators to update this status.
- [ ] Implement a basic 'Contact Us' form using ActionMailer.
