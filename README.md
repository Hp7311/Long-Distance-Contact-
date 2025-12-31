# LDC (Long Distance contact)

LDC is a small tool that tells you and your friend which direction to look in so you’re technically facing each other across long distances.

No, you cannot actually see each other.
Yes, this is still fun.

## What it does
- Takes latitude and longitude of two people
- Calculates the compass bearing from person A to person B
- Calculates the reverse bearing for person B

## What it does NOT do
- Create real eye contact
- Break physics
- Replace video calls

## How it works (very briefly)
- Uses latitude and longitude (in degrees)
- Converts them to radians
- Applies trigonometry to calculate bearings on a spherical Earth
- Outputs angles between 0° and 360°

## How to use

Run the script:
```bash
python ldc.py
