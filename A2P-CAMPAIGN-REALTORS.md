# A2P 10DLC — Campaign #2: Property Alerts for Real Estate Professionals

Copy-paste answers for Twilio Console → Messaging → Regulatory Compliance → A2P 10DLC → **Create new campaign** (same Brand: Condo Black Book LLC, APPROVED / Standard).

Before registering: deploy `/realtors` and make sure https://messages.blackbookproperties.com/realtors, /terms and /privacy load publicly. Create a NEW Messaging Service first (e.g. "BBP Realtor Property Alerts") and put the new 786 number in it; the campaign is attached to that service.

---

## Campaign use case
**Marketing**

(Not "Mixed": this program only sends promotional/alert content. Keep the existing Low Volume Mixed campaign for Ana and client coordination.)

## Campaign description
Blackbook Properties (Condo Black Book LLC), a licensed Miami real estate brokerage, sends recurring property alert text messages to licensed real estate agents, brokers and MLS members who opt in on our website at https://messages.blackbookproperties.com/realtors. Messages include new listings and inventory, price changes, pre-construction releases, off-market opportunities and Miami market data that agents use to serve their buyers. Recipients are real estate professionals who subscribe voluntarily; consent is not a condition of purchase or of doing business with us. Every message identifies Blackbook Properties and includes opt-out instructions. Frequency is up to 8 messages per month. Recipients can reply STOP to cancel at any time and HELP for assistance.

## Message flow / how end users opt in
End users opt in on the web form at https://messages.blackbookproperties.com/realtors. They enter their name, mobile phone number and email, and must actively check an unchecked consent box that reads: "Yes, text me property alerts. By checking this box, I agree to receive recurring automated marketing text messages from Blackbook Properties (Condo Black Book LLC) at the mobile number provided, including new listings, price changes, pre-construction releases and Miami market data. Consent is not a condition of any purchase or of doing business with Blackbook Properties. Message frequency: up to 8 messages per month. Message & data rates may apply. Reply STOP to cancel at any time. Reply HELP for help." Links to the Privacy Policy (https://messages.blackbookproperties.com/privacy) and SMS Terms (https://messages.blackbookproperties.com/terms) are shown next to the checkbox. The form cannot be submitted without the box checked. After submitting, the user receives a confirmation text with the program name, frequency, STOP/HELP instructions and the message-and-data-rates disclosure. Consent records (timestamp, consent text, source URL) are stored. No phone numbers are purchased, rented or shared.

## Opt-in keywords
(leave empty — web form only)

## Opt-in confirmation message
Blackbook Properties: You're subscribed to Property Alerts for real estate professionals. Up to 8 msgs/month. Msg & data rates may apply. Reply STOP to cancel, HELP for help.

## Opt-out keywords
STOP, STOPALL, UNSUBSCRIBE, CANCEL, END, QUIT

## Opt-out message
Blackbook Properties: You have been unsubscribed from Property Alerts and will receive no further messages. Reply START to re-subscribe.

## Help keywords
HELP, INFO

## Help message
Blackbook Properties Property Alerts: for help email operations@blackbookproperties.com or call (305) 697-7667. Reply STOP to cancel. Msg & data rates may apply.

## Sample messages (20–200 chars, brand named, opt-out included)
1. Blackbook Properties: New listing at [Building], [Unit] — [Beds]/[Baths], [Price]. Details: [Link]. Reply STOP to opt out.
2. Blackbook Properties: Price change at [Building] [Unit], now [Price] (was [OldPrice]). Reply STOP to opt out.
3. Blackbook Properties: Pre-construction release — [Project], [Neighborhood], from [Price]. Floor plans: [Link]. Reply STOP to opt out.
4. Blackbook Properties: Off-market opportunity in [Neighborhood], [Beds]/[Baths], [Price]. Reply YES for details or STOP to opt out.
5. Blackbook Properties: Miami market update — [Month] closed sales [Number], median [Price] in [Neighborhood]. Report: [Link]. Reply STOP to opt out.

## Message contents
- Embedded links: **Yes** (links to condoblackbook.com listing pages and market reports; no public URL shorteners)
- Embedded phone numbers: **Yes** ((305) 697-7667 in HELP message)
- Age-gated content: No
- Direct lending / loan arrangement: No
- Affiliate marketing: No

## Privacy policy URL
https://messages.blackbookproperties.com/privacy

## Terms and conditions URL
https://messages.blackbookproperties.com/terms

## Opt-in proof (screenshot/URL)
https://messages.blackbookproperties.com/realtors
(Take a screenshot of the form with the consent box visible and attach it too.)

## Expected volume
Low Volume Standard is fine to start (under 2,000 segments/day). Upgrade to Standard if the subscriber list grows past ~1,500.

---

### After approval
1. Attach the new 786 number to the "BBP Realtor Property Alerts" Messaging Service (sender pool).
2. Send from that Messaging Service (not from the raw number) so the campaign is applied.
3. Keep the two programs separate: never send property alerts from Ana's or CBB's numbers.
