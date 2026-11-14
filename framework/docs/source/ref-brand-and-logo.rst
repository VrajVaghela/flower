:og:description: Flower logo files in this repository, the usage statements Flower has published, and the questions those statements leave open.
.. meta::
    :description: Flower logo files in this repository, the usage statements Flower has published, and the questions those statements leave open.

#################
 Brand and logo
#################

This page lists the Flower logo files shipped in this repository and the usage
statements Flower has already published. It records those sources only. Questions
that those sources leave open are listed in :ref:`brand-and-logo-open-questions`.

.. _brand-and-logo-files:

********************************
 Logo files in this repository
********************************

The framework documentation theme loads two PNG files from
``framework/docs/source/_static/``. ``framework/docs/source/conf_base.py`` sets
``light_logo`` to ``flower-logo-light.png`` and ``dark_logo`` to
``flower-logo-dark.png``.

``flower-logo.png`` and ``flower-logo-light.png`` are the same bytes. Each file
is a 641 by 641 PNG of the flower mark and the words "Flower Framework" on a
light background.

.. figure:: ./_static/flower-logo-light.png
    :alt: Flower Framework logo on a light background, used by the light theme
    :align: center
    :width: 240px

    ``flower-logo-light.png``, identical to ``flower-logo.png``. The width above
    is only the size of this figure.

``flower-logo-dark.png`` is a 641 by 641 PNG of the flower mark and the words
"Flower Framework" on a dark background. In this file, the word "Framework" is
yellow.

.. figure:: ./_static/flower-logo-dark.png
    :alt: Flower Framework logo on a dark background, with the word Framework in yellow
    :align: center
    :width: 240px

    ``flower-logo-dark.png``. The width above is only the size of this figure.

Other documentation sets in this repository ship their own logo PNGs. These
files are separate from the two framework theme logos:

- ``baselines/docs/source/_static/flower-logo.png``
- ``examples/docs/source/_static/flower-logo.png``
- ``hub/docs/source/_static/flower-logo.png``
- ``datasets/docs/source/_static/flower-datasets-logo.png``
- ``agent/docs/source/_static/flower-agent-logo-light.png``
- ``agent/docs/source/_static/flower-agent-logo-dark.png``

.. _brand-and-logo-published-statements:

******************************
 Statements already published
******************************

**Apache License, Version 2.0**

The repository ``LICENSE`` file is the `Apache License, Version 2.0
<https://www.apache.org/licenses/LICENSE-2.0>`_. Section 6 states:

    6. Trademarks. This License does not grant permission to use the trade names,
    trademarks, service marks, or product names of the Licensor, except as
    required for reasonable and customary use in describing the origin of the
    Work and reproducing the content of the NOTICE file.

That section names trade names, trademarks, service marks, and product names.

**Flower Visuals**

The Flower Visuals page, as captured by the Internet Archive on 14 December
2024, published these statements:

- "Our visuals and templates are licensed under a Creative Commons
  Attribution-NonCommercial-ShareAlike 4.0 International License. The Flower
  Logo is not part of the Creative Commons License and is a registered
  trademark."
- "The Flower Logo is a registered trademark. Any misuse is strictly
  prohibited."
- A "Flower Brand Design elements" section offered the Flower logo and logo
  variants from `this Google Drive folder
  <https://drive.google.com/drive/folders/1gqy7MHIZfcG9ITDOrxi87DmftdfYZdE4>`_.

The Creative Commons license linked from that page is `CC BY-NC-SA 4.0
<https://creativecommons.org/licenses/by-nc-sa/4.0/>`_. The same page said that
the Flower logo sits outside that license.

Archived copy: `Flower Visuals (14 December 2024)
<https://web.archive.org/web/20241214012419/https://flower.ai/visuals/>`_.

On 14 November 2026, a request to ``https://flower.ai/visuals/`` returned a
redirect to ``https://flower.ai/``.

**Flower Labs Platform Terms of Service**

Section 16.1 of the `Flower Labs Platform Terms of Service
<https://flower.ai/legal/terms-of-service>`_ states:

    You shall not use our company name and logo or publish any press release or
    other public communication without our prior consent.

Section 1.2 of those terms defines "You" as the customer of the platform
services: an individual user, or a business organization, that enters the
agreement. The terms describe the Flower Labs platform services.

**Design language post**

The 11 May 2022 post `Flower's new Design Language
<https://flower.ai/blog/2022-05-11-flowers-new-design-language>`_ describes how
the visual design was chosen. The post links a file titled "Flower Design
Guide" (Google Drive file id ``1sXqvqeEeMvAISIsGUImOuzvLmQgMeMaS``). This page
does not restate that guide.

.. _brand-and-logo-open-questions:

***************
 Open questions
***************

Flower has not published answers to the questions below. This page leaves them
open for the maintainers.

1. `Issue 8501 <https://github.com/flwrlabs/flower/issues/8501>`_ asks whether a
   community member may place the Flower logo in a blog post, a talk, or a
   "built with Flower" mention when the logo only identifies the project. The
   reported case is a company post about that company's own contribution,
   written so that it does not claim a partnership with, or an endorsement by,
   Flower Labs. The issue has no comments.
2. Whether section 16.1 of the platform Terms of Service applies only to
   customers who have accepted that agreement.
3. Whether the 14 December 2024 Flower Visuals statements are still in force.
   That includes the registered-trademark wording, the sentence "Any misuse is
   strictly prohibited", and the CC BY-NC-SA 4.0 license for visuals and
   templates other than the logo. The live ``/visuals/`` URL now redirects to
   the home page.
4. Which files are the canonical logo download for use outside this
   documentation. The sources above name the PNGs in
   ``framework/docs/source/_static/`` and the Google Drive folder linked from
   Flower Visuals. The repository does not state a license for reusing the
   documentation PNGs. This page also does not list the current contents of
   that Drive folder.
5. Clear space, minimum size, required colors, modification, animation, and
   merchandise. The sources quoted on this page do not state them.
6. Usage rules for the Flower Datasets and Flower Agent logo files listed
   above.
7. What the Flower Design Guide linked from the 2022 post requires. A request
   for that Drive file returned HTTP 404 on 14 November 2026, so its contents
   are not included here.
