# HubSpot Forms Listener

Sends a dataLayer event with the form ID whenever HubSpot accepts a form submission. Works with forms from the new and legacy HubSpot editors. Rejected attempts are never counted.

## Setup

Follow the [setup guide](https://converly.io/gtm-templates/hubspot-forms).

Set this tag to fire on All Pages so it listens on every page with a HubSpot form. Then fire your conversion tags from a Custom Event trigger on hubspot_form_submitted.

## Event

The listener sends hubspot_form_submitted. Use CE - HubSpot Form Submitted as the custom event trigger.

## Script

The template loads https://gtm-templates.converly.io/hubspot-forms-listener.js.

## Notes

Pushes one hubspot_form_submitted event, with the HubSpot form ID, each time HubSpot accepts a submission. It never reads the answers or any other personal data, and your forms keep working exactly as they do today. Full setup guide at https://converly.io/gtm-templates/hubspot-forms

## License

Apache License 2.0.
