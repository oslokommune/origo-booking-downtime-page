# origo-booking-downtime-page
Nedetid side for origo booking

For å aktivere lag CNAME record for

nedetid.booking.oslo.kommune.no -> oslokommune.github.io

Lag ny regler i ALB som tar trafikk fra booking.oslo.kommune og eller admin.booking.oslo.kommune og gjør en 302 redirect til nedetid.booking.oslo.kommune
