# Platter

**Reliable help, on a silver platter.**

Platter is an online artisan platform that helps customers find service performers around them. It covers a wide range of trades and services, including carpenters, masons, electricians, plumbers, fashion designers, mechanics, and food services.

## The problem

Finding the right service performer is often stressful and can take days. Platter removes that wait by connecting customers with reliable artisans quickly.

## How it works

Platter is a two-way platform:

- **Customers** browse or search for a service, view provider profiles, and send a job request.
- **Service providers** set up a profile with their trade, area, rates, and past work, then receive and respond to job requests.
- **Admins** verify providers before they go live and handle reports.

## Status

Early design stage. Wireframes and the visual design are complete, and the technical plan is next. No app code yet.

## Launch plan

Platter will start with a small pilot instead of a wide launch:

- Begin with a limited set of trades tied to home improvement: tiling, kitchen cabinet and door installation, carpentry, plumbing, electrical, and painting.
- Test with real customers and artisans connected to a home-improvement store, where customers already ask for recommended installers.
- Learn from the pilot, then expand to more areas and services.

## MVP scope

**Included in the first version**
- Phone number sign-up and verification
- Browse by trade and view provider profiles with photos and reviews
- Request a job with a description, photos, and a preferred date
- Provider dashboard with an availability toggle and incoming requests
- Reviews after completed jobs
- Admin screens for provider verification and reports

**Planned for later**
- In-app payments (mobile money)
- Automatic matching to the nearest available provider
- More service categories, such as food and fashion
- Subscriptions and promoted listings

## Planned tech stack

Not final. Under consideration:

- Flutter for Android first, then iOS
- Firebase or Supabase for the database, accounts, and file storage
- Phone number sign-in with an SMS code
- Push notifications
- A simple web dashboard for admin

## Repository structure

```
platter-app/
├── design/
│   ├── logo/          Logo files (wordmark and emblem)
│   └── screens/       Wireframes and visual design exports
├── docs/              Technical plan and project notes
└── README.md
```

## Brand

- **Typeface:** Montserrat
- **Brand teal:** `#65B0A6`
- **Darker teal for text and buttons:** `#2A766D`

## Contributing

This is a private project. Work on new features in a separate branch and merge it into `main` with a pull request once it works.
