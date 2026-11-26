# Mobilne Saunowanie

A mobile-first website for a family-run wood-fired sauna rental business on the Polish coast. Customers can check rental prices and the delivery area, then call to book.

## Technical notes

Astro generates static HTML and responsive WebP images at build time. The photo gallery uses a native HTML dialog with keyboard navigation. Each thumbnail also links directly to the larger image, so visitors can open photos with JavaScript disabled.

The booking phone number (`BOOKING_PHONE`) and owner name (`BOOKING_OWNER`) are configured as environment variables on the hosting platform, outside the Git repository. The production build includes both values in the public HTML.
