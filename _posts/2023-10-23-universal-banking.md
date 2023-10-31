---
title:  "Universal banking"
date:   2023-08-19 12:10:00 -0400
categories: informatics
authors: ismaelc
status: draft
---

## Services

- **Multiple currencies:** All currencies present in the world can be stored in the bank account, each with his own amount.
- **Worldwide use of ATMs:** It's possible to withdraw in any ATM, by converting from your currencies to a currency supported by the ATM (which is usually one), or withdrawing from that currency if that currency is present in the bank account.
- **Debit card** can be used to buy online with the respective currency. It's possible to make conversions from your currencies, if needed.
- **Virtual cards**, which can be used instead of the debit or credit card, to do transactions in name of that card.
- There can be more than one person using the same bank account, which is assigned with virtual cards for all persons different than the owner. Those persons are intended to be family members.

## Universal taxation number

The **Universal Taxation Number** (**UTN**) is an unique identification number for doing taxations, in order to identify the person, organization or group doing the transaction.

It's composed, in order, from the following parts:

- **Planet identifier:** It identifies the planet of origin of the person. It's written as the name of the plannet in uppercase letters.
- **Country identifier:** It identifies the country of origin of the person. It consists of the country code of the ISO of countries, in uppercase letters.
- **Random number:** It's a unique number generated randomly.
- **Check digit:** It's a number calculated from the random number, consisting of three digits, that allow to verify that the random number written is correct.

All the different parts are separated by dashes. It's **forbidden** to assign the same UIN and UTN to the same person, they must be always different for everyone.

## List of purchases

All the purchases list the products with their name. The name of the store appears, which is the normal name of the store, not another.

## Plugin of currencies for web browsers

Web browsers can convert a currency to another, with the present conversion, in any webpage.

## ER model
