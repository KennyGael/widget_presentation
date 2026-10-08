# Width & Height: Flutter Profile Card

A Flutter demo that shows how the `width` and `height` properties size the widgets in a profile card (banner, avatar, buttons, and progress bar).

## How to Run

1. Make sure [Flutter](https://docs.flutter.dev/get-started/install) is installed (`flutter doctor` should pass).
2. Clone the repository:
```bash
   git clone https://github.com/KennyGael/widget_presentation.git
   cd widget_presentation
```
3. Get dependencies:
```bash
   flutter pub get
```
4. Run the app on an emulator, simulator, or connected device:
```bash
   flutter run
```

## The Three Attributes

1. **`width`**: Sets the horizontal size of a widget. The card is 300 px wide, the banner fills the card (`double.infinity`), the avatar is 80 px, each button is 120 px, and the progress bar is 260 px with a 180 px filled portion.
2. **`height`**: Sets the vertical size. The card is 460 px tall, the banner is 120 px, the avatar is 80 px, the buttons are 44 px, and the progress bar is 10 px.
3. **`decoration`**: Styles the box that `width` and `height` define, using `BoxDecoration` for color, `borderRadius` (16 on the card, 5 on the progress bar), and `shape: BoxShape.circle` (the avatar).

## Screenshot

<img width="224" height="384" alt="Screenshot 2026-10-08 191001" src="https://github.com/user-attachments/assets/62a665c2-d19a-4a4b-89d6-50344b229d76" />
