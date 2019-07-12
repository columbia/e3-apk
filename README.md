# e3-apk
Precompiled APKs for Easy Email Encryption (E3).

The E3 prototype for Android requires the use of two applications modified to support E3:

* K-9 Mail
* OpenKeychain

Please install both, then proceed through account setup in K-9 Mail as usual.

# Initial Setup

1. Install K-9 Mail and OpenKeychain from this repository.

2. Open K-9 Mail and provide your email account credentials in the account setup steps.

3. You will be asked to Allow Access to OpenKeychain - select Allow.

4. Wait while the PDK key is generated.

5. Select the newly generated PDK key.

6. (Optional) Press "Start Synchronization" to begin the process of synchronizing your E3 devices if you have other E3 mail clients.

# E3 Settings

You may access E3's settings via Settings > (account name) > Encrypt on receipt (E3).

# Device Synchronization

1. Go to E3's settings via Settings > (account name) > Encrypt on receipt (E3).

2. Press "Manual device synchronization".

3. Press "Start E3 Synchronization" and take note of the displayed three word phrase.

4. Wait until the "New E3 Device Detected" notification appears on your other device with E3.

5. Select the notification and then select the previously displayed three word phrase.

6. Now take note of the new three word phrase, and wait for the "New E3 Device Detected" notification on the original device.

7. Repeat step 5 on the original device.
