# Notes
- You can expect to pay 20c - 30c per card. Obviously some cards you may as well just buy.
- There is a step that can be lengthy and require a few minutes if you have a lot of cards to order.


# Setup
- Make/have an account at https://www.makeplayingcards.com/
- Install/have Chrome
- Go to https://github.com/chilli-axe/mpc-autofill/releases/
- Download autofill-windows.exe

NOTE: The largest card order to easily place with mpcfil.com is 612 cards.

https://mpcfill.com/

- Search Settings
  - Click Disable All Drives
- Enable and priotize Drives
  - RustyShackleford (for original-close and MDFC)
  - WillieTanner
- Upload card list as text (or whatever)
  - Enter cards in the following format
```
1x Mountain
2x Island
```
- Set Cardback
  - 24/424 is an textless version the standard Magic cardback
- Download the XML file
- Make sure the .xml and autofill-windows.exe are in the same folder
- Run autofill-windows.exe
- Choose Chrome
- Choose MakePlayingCards
- Choose Y to auto save
- Choose Y to process images to reduce uplaod times (this downscaling is still above what MakePlayingCards.com prints at)
- Sign in
- Choose one or more .xml files in the same directory.
- After the automation continues, Click the checkbox and then Add to Cart
  - NOTE: This can easily take 5-10 seconds PER CARD.
Change to a different browser (one not controlled by the automation script)
- Verify all the cards are there
- Open Firefox and log in to makeplayingcards, begin checkout process
- When the Payment Method screen is shown with only Credit Card as a selection, create and visit a bookmark with this url
  - javascript:paymentMode('4319D0A447FDC73F');
- Now you can check out with Paypal.
