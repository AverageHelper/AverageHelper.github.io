+++
title = "The System is Wack: Will Kiosk For Food"
author = "James Robinson"
date = 2021-10-25T13:45:00-06:00
categories = ["Troubleshooting", "Shopping", "Food"]
tags = ["cloud", "kiosk", "food", "eatery", "someone else's computer", "Apple Card"]
+++

![A news clipping from the Simpsons: "Old Man Yells at Cloud," with picture of Grampa Simpson shaking his fist at a cloud in the sky.](/img/posts/2021-10-25-will-kiosk-for-food/old-man-yells-at-cloud.jpg)
_Me when computer no work_

# TL;DR

Make sure someone else looks at your product, for a good long time, before it becomes the _only_ way people get food.

# Background

Computers can do a lot of good. They can do a lot of bad. Sometimes, they're just annoying.

I went to my local food court today for lunch. This was the first time in many months, possibly years, that I'd been here to eat. I had a hankering for some Hawaiian food, so I went down to get me some.

# Getting There

Things were different. One does not simply talk to a cashier to order food here anymore. One approaches a kiosk, composes their order, and pays digitally. Easy, right? I had on me two cards with which I could pay: a club card that worked at this food court, and my credit card. The club card would eat from my bank account, but it would aggregate transactions with other recent purchases on my account, which muddies the receipt I get via email, and is generally a hassle for organizing receipts. My credit card... is a credit card. I get no email receipt by default, but my transaction would show up on my statement, with location and timestamp details, well-organized as I like them. When I approached the nearest working kiosk, I chose to use the credit card.

This was my first mistake.

## The Order

The ordering process was subpar at best. This kiosk computer was slow as molasses. Every tap had about 2 seconds of reaction delay on the screen. Drag-scrolling worked, but the screen was nasty with the grease of many food-laden and food-hungry hands. Meal combos are the default subheading, and require the full suite of combo items to be selected: entrée, drink, and ice cream. I just wanted the entrée!

I cancelled my selection and found the menu where I could select what I want to eat. This already took long enough to annoy the person behind me. (Probably. I assume they were annoyed. I would have been annoyed.)

I finally got my order together. Great, right? The machine wants my phone number now. _Lol no,_ I thought smugly to myself as I pressed the difficult-to-reach "Skip" button. _Why does this machine need my phone number? I'll just get a receipt._

I swiped my card, waited for my receipt, and... nothing. There was a brief _*bzzzt*_ from the receipt dispenser. The words "New Order" stared me down from the screen. The little "Receipt Here" sign by the dispenser taunted me, unmoving.

There was no receipt.

Normally, this was fine. A cashier would have got my name by now and put that with the order.

The machine did not know my name.

I'd have got a text with my order details, if I had put in my phone number.

The machine did not know my phone number.

As the kitchen called out order number after order number, I realized that my options were limited. Plus, I was holding up the line at the only working kiosk. I gave the machine a sour look, then moved aside toward the crowd of people waiting to hear their order number.

## What Do?

I asked some friends on Discord. They'd been to this food court, some of them regularly. "You'll get a text," one said. "Give the attendant your credit card number," said another.

The phone number would not work, because I never gave the machine my number.

The credit card idea might work to fish out my order number, but I do not know my credit card number. That number is not printed on my card, you see. Think [Apple Card](https://www.apple.com/apple-card/). I can't give the attendant a number that I do not have.

"If you have your credit card's bank app on your—"

I don't.

That app is on my secondary phone, which I normally leave at home. I had not anticipated that I'd need to show my credit card number. Besides, I've never before considered that possibility that I might need to show proof of payment using my credit card statement, of all things!

I had two options: (1) flag down the attendant, throw off his groove, make a fuss, and try feebly explain the problem to a manager through a face mask, or (2) wait for food that looks like mine to sit on the counter for a while.

I chose option 2.

## The Food

About ten minutes later, an average wait time, I got some food. Maybe it was my food, maybe it was someone else's, I can't be too sure. My order was a fairly common one. I'm sure someone else got my plate if I got theirs, and that's no skin off either of our backs. The food tasted fine.

# The Point

"The system is wack," as I like to say. I'm only half joking.

These kiosks are meant to simplify food-getting, perhaps by freeing up manpower for handling orders, or maybe by reducing patrons' ordering mistakes. When I ordered food here in years past, the same person that took the orders would call out food done for people. The lines were long both to order and to get food, the attendant was stressed and overworked, and me standing around _not_ scrolling social media felt really awkward. All of it was a bit overwhelming for everyone involved.

Credit where credit is due, the kiosk seemed to help; today's line wasn't very long to order. The kiosk was also the most frustrating part of the process for me.

The programmers of this kiosk's software missed one important bundle of considerations: the receipt printer. I got my food because, luckily, I knew what my order would look like. Luckily, the attendant believed me when I said the receipt machine is out of paper and I'm _totally_ number 83. 😅 Luckily, I'm not the sort of person to raise a public fuss over $6 of food.

The kiosk wasn't designed to create this sort of confusion. When every user follows the "happy path," the one where I use my club card, provide my phone number, and the receipt printer has paper, everything is fine! The programmers chose to make important form elements optional (like my phone number), never considering that the receipt might not exist. The programmers chose to omit the order number from the confirmation screen, never considering that receipt paper could run out at any time. The programmers possibly never considered adding a prompt, in case the printer ran out of paper, to ask the user for a phone number or email address so they might have some sort of payment confirmation. This series of small decisions led to a slightly-broken system, and frustrated one user enough for them to write up a blog post about it.

I can't assume much about the process this machine went through between implementation and testing, but more QA (Quality Assurance) testing wouldn't hurt.
