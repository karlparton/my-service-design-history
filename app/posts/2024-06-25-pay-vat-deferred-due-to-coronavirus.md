---
title: Pay VAT deferred due to coronavirus (COVID-19)
description: To support businesses during the COVID-19 crisis the government announced VAT payments would be deferred for a three month period. 530,000 businesses deferred a total of £38.3bn in VAT.
date: 2021-03-20
---

## Situation

To support businesses during the COVID-19 crisis the government announced VAT payments would be deferred for a three month period. 530,000 businesses deferred a total of £38.3bn in VAT.

## Task

Design a service to enable businesses to set up a direct debit to pay their deferred VAT.

## Action

* Worked remotely as part of a multidisciplinary team
* Produced user flows
* Produced a service map
* Participated in remote user research sessions
* Participated in remote customer empathy workshop
* Designed and built 3 iterations of the service prototype
* Continued to iterate the service during private beta
* Participated in Government Digital Service peer review

## Result

Within the first 5 weeks

* 100k plus registrations
* £10.16bn worth of direct debits added to the scheme

### User flow

![A crown icon above the words GOV.UK](/images/pay-vat-deferred-due-to-coronavirus/misc/customer-journey-crop.png "Snapshot: 3 routes into the service.")
*Snapshot: 3 routes into the service.*

### Service map
![A crown icon above the words GOV.UK](/images/pay-vat-deferred-due-to-coronavirus/misc/service-map.png "I worked with a content designer and a user researcher to produce a service map.")
*I worked with a content designer and a user researcher to produce a service map.*

## User research private beta

### Key findings

* Displaying the number of months and the amount calculated per month, users were able to chose the time period that worked best for them.
* Users were split 50:50 between those that chose the longest possible timescale to pay and those that wanted to clear the deferred VAT amount as quickly as possible.
* Users wanted to see the payment schedule immediately after choosing their monthly payments.

### Quotes

> Incredibly simple, straightforward, gets 10 out of 10 - Bastion Construction

> Really straightforward, I don't think there is anything missing, it was easy for me to navigate round, which means it should be fine for anybody else - Learning4leaders

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Total deferred vat bill",
      img: { src: "01-total-deferred-vat-bill.png" }
    }, {
      text: "Do you want to pay in monthly instalments?",
      img: { src: "02-pay-in-instalments.png" }
    }, {
      text: "How many months do you want to pay over?",
      img: { src: "03-how-many-months-to-pay.png" }
    }, {
      text: "Check your payment plan",
      img: { src: "04-check-payment-plan.png" }
    }]
}) }}

