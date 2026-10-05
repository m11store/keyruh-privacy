# KeyRuh Privacy Policy

**Effective date:** October 5, 2026  
**Applies to:** KeyRuh for Windows, version 0.1.0

## Summary

KeyRuh processes keyboard-layout conversions locally on your Windows device. The
application does not send selected text, keyboard input, or conversion results
to KeyRuh servers. It does not include an account system, advertising, analytics,
or application telemetry.

## Keyboard shortcut and clipboard

When KeyRuh is enabled, it monitors keyboard events locally to recognize the
global shortcut configured by the user. It does not record or retain general
keystroke history.

When the shortcut is activated with text selected, KeyRuh converts the text
instantly and locally on the device without storing or leaving converted text
entries in the Windows clipboard history. KeyRuh does not transmit, store, or
log any converted text or clipboard data.

## Settings and storage

KeyRuh stores application settings locally, including the shortcut, background
mode, startup preference, and any custom keyboard-layout changes. These settings
are not uploaded by KeyRuh. Converted text and general keystroke history are not
stored as application data.

## Permissions and why they are used

The Windows desktop application uses a global keyboard hook to detect the
user-configured shortcut, and clipboard access to convert selected text. These
operations are necessary for conversion to work in other applications. The
keyboard hook is used to detect the configured shortcut; it is not a keylogger.

The Microsoft Store MSIX package template requests the `runFullTrust`
capability, which is required to run this Win32 desktop application. Windows
does not provide a separate MSIX manifest capability for a low-level keyboard
hook. The Store submission must clearly explain and justify this behavior.

## Third-party services

KeyRuh does not use a KeyRuh-operated server to process text. Windows, the
Microsoft Store, WebView2, and other software installed by the user are
independent services and may process data under their own privacy terms.

## Changes and contact

This policy may be updated when the application’s behavior changes. For privacy
questions, contact:

**Privacy contact:** [Matar.111@outlook.sa](mailto:Matar.111@outlook.sa)
