id: temporary-email-model
title: TemporaryEmail Model
sidebar_label: TemporaryEmail Model
---

# TemporaryEmail Model

## Overview

The `TemporaryEmail` model is designed to temporarily store email addresses along with a One-Time Password (OTP) that is used for email verification processes. This model is typically used in scenarios where an email address needs to be validated before it can be associated with a user's profile in the system.

## Model Definition

Here is the model definition for the `TemporaryEmail` class:

```python
class TemporaryEmail(models.Model):
    email = models.CharField(max_length=100)
    otp = models.CharField(max_length=100, null=True, blank=True)
    created_at = models.DateTimeField(auto_now_add=True)
    confirmed = models.BooleanField(default=False)

### Fields Description

- **email** (`CharField`):
  - **Description:** Stores the email address that needs to be verified.
  - **Type:** String
  - **Max Length:** 100 characters
  - **Null:** No (This field is required)

- **otp** (`CharField`):
  - **Description:** Stores the One-Time Password (OTP) sent to the email address for verification. This field can be null or blank if the OTP has not been generated yet.
  - **Type:** String
  - **Max Length:** 100 characters
  - **Null:** Yes (Optional)
  - **Blank:** Yes (Optional)

- **created_at** (`DateTimeField`):
  - **Description:** Records the date and time when the `TemporaryEmail` instance was created. This field is automatically populated when the instance is created.
  - **Type:** DateTime
  - **Auto-Add:** Yes (Automatically set to the current date and time when the record is created)
  - **Null:** No (This field is required)

- **confirmed** (`BooleanField`):
  - **Description:** Indicates whether the email has been successfully confirmed using the OTP. The default value is `False`, meaning the email is not confirmed until the verification process is completed.
  - **Type:** Boolean
  - **Default:** `False` (Not confirmed)

### Usage Example

The `TemporaryEmail` model can be used in the following scenarios:

- **Email Verification During Sign-Up:**
  - When a user signs up, their email address is stored in the `TemporaryEmail` model along with an OTP that is sent to their email. The email is not confirmed until the user submits the correct OTP.

- **Password Reset:**
  - During a password reset process, an OTP can be sent to the user's email, and the email can be stored in the `TemporaryEmail` model until the OTP is verified.

- **Two-Factor Authentication (2FA):**
  - The model can also be used in 2FA processes where an email address needs to be verified before granting access.
