Portal Sale Personal Data Only
This repository bundles OCA modules `portal_sale_personal_data_only` and `portal_account_personal_data_only` so they can be installed together.


Beta License: AGPL-3 OCA/sale-workflow Translate me on Weblate Try me on Runboat

By default, portal users are allowed to see all the sale orders in which a member of their organization are followers. That could cause a leaking of documents between members and departments and of the organization that should stay private.

This module restricts that behaviour so the portal users only see their own documents.

Table of contents

    Usage
    Bug Tracker
    Credits
        Authors
        Contributors
        Maintainers

Usage

    Create some portal users belonging to the same company.
    Place some orders for several of these users.
    Log in with each portal user credential.
    Only the sale orders belonging to the logged in user's partner or his descendants should be accessible.
    Invoices associated to a partner's sale order will be visible as well.

Bug Tracker

Bugs are tracked on GitHub Issues. In case of trouble, please check there if your issue has already been reported. If you spotted it first, help us to smash it by providing a detailed and welcomed feedback.

Do not contact contributors directly about support or help with technical issues.
Credits
Authors

    Tecnativa

Contributors

    Harald Panten <harald.panten@sygel.es>
    Tecnativa:
        David Vidal
        Víctor Martínez
        Stefan Ungureanu
    Moaad Bourhim <moaad.bourhim@gmail.com>
    Jairo Llopis (Moduon)
    SodexisTeam <dev@sodexis.com>

Maintainers

This module is maintained by the OCA.
Odoo Community Association

OCA, or the Odoo Community Association, is a nonprofit organization whose mission is to support the collaborative development of Odoo features and promote its widespread use.

This module is part of the OCA/sale-workflow project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
