# gnome-icc-profiles

A collection of standard ICC color profiles for GNOME desktop and Linux color management systems.

## Included Profiles

- **RGB Color Spaces**: AdobeRGB (1998), Apple RGB, BestRGB, BetaRGB, BruceRGB, CIE-RGB, ColorMatch RGB, DonRGB4, ECI-RGB (v1 & v2), EktaSpace PS5, NTSC-RGB, PAL-RGB, ProPhoto RGB, Rec.709, SMPTE-C, sRGB, and Wide Gamut RGB.
- **CMYK & Print Standards**: FOGRA (27L, 28L, 29L, 30L, 39L, 40L, 45L, 47L), GRACoL TR006, IFRA26S (2004), SNAP TR002, and SWOP (TR003, TR005).
- **Color Temperature & Gamma**: Gamma 5000K, 5500K, and 6500K.
- **Testing & Diagnostics**: Bluish, Crayons, SwappedRedAndGreen, and x11-colors.

## Installation

### Current User

Copy the profiles to your local ICC directory:

```bash
mkdir -p ~/.local/share/icc
cp *.icc ~/.local/share/icc/
```

### System-wide

Copy the profiles to the system color directory:

```bash
sudo cp *.icc /usr/share/color/icc/
```

## Usage

1. Open **Settings** in GNOME.
2. Navigate to **Color**.
3. Select your display or device.
4. Click **Add profile** and choose the desired profile.
