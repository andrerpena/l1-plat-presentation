The future of LegaLOne
===

Hi. My name is Andre Pena and on this video, I'm going to present what we envisioned as the future of LegalOne as a platform.
What I'm about to present is the result of years of meetings and discussions 
 
 What is LegalOne?
 ---
 
LegalOne is an Enterprise resource planning solution, or an ERP, that is focused on law firms and legal departments.
So, first, what is an ERP?
 
From Wikipedia, an ERP is:

... A business-management software, typically a suite of integrated applications, that an organization can use to collect, store, manage and 
interpret data from many business activities, including:

 - product planning, cost
 - manufacturing or service delivery
 - marketing and sales
 - inventory management
 - shipping and payment
 
Or you can just say an ERP is the software solution that a businesses use for managing most, if not all, of the data in 
their operations. That's why ERP systems are also called data-centric business applications. In the specific case of
LegalOne, we provide a variety of solutions for our customers like accounting, billing, time tracking, services management 
and time tracking and, most importantly, matter management.

Is LegalOne a product or a platform?
---

LegalOne started out as a product called Novajus, which was origninally aimed at law firms. However, because Novajus was a fast-growing product and it had a favorable architecture, we saw the potential to turn it into something bigger. We wanted to be able to leverage the core features, like the user interface, security, auditing, customizable reports and so forth, and allow for specific business rules to be customized, in such a way that Novajus could reach out new markets, like legal departments, or even new regions. Then, we started adding platform characterists to Novajus, and the result of that effort would later be named LegalOne.

You are probably familiar with this diagram. We designed an architecture that allows customizations to be added through layers. We can, then, ship multiple products just by  Each layer leverages everything from the layers beneath, and it allows for overriding existing artifacts.

Artifacts that can be  customized include:

 - Services: That makes it possible to customize existing business rules, as well as adding new ones. For instance, if you want an appointment to be created everytime a matter is created, you can implement a new MatterService, that overrides an existing MatterService, and then you can implement this rule.
 - Views: That makes it possible to create customized forms for specific entities. For example, If you want to remove some fields and add new fields to the Matters form, you can implement a new EditMatter view, and then change it according to the requirements.
 - Look and feel: That makes it possible for products to have customized styles.
 - Localization, including translation, currencies, time-zones and date and number formats.
 - Others...

So, going back to the subject. Is LegalOne a product or a platform? The answer is: LegalOne is a product that has many platform features. Is it possible to deliver multiple products on top of LegalOne, as it is today? Yes, but there's room for improvements, and that's what this whole presentation is about.


