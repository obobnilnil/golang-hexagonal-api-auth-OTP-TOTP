<div align="center">
    <img src="https://neonxp.gallerycdn.vsassets.io/extensions/neonxp/gotools/0.1.5/1691451648679/Microsoft.VisualStudio.Services.Icons.Default" alt="Gin" width="400"/>
    <img src="https://user-images.githubusercontent.com/4400999/75789359-8ee24780-5d37-11ea-9710-15eea7a51241.png" alt="2fa" width="350"/>
</div>
<H1>ReadME</H1>
This Golang-based code demonstrates how to create an API using the Gin framework to implement two-factor authentication (2FA). It validates OTPs via email and TOTPs through authenticators such as Google Authenticator, Microsoft Authenticator, LINE-Application, and others. The code is written using hexagonal architecture.
<div align="center">
    <img src="https://github.com/user-attachments/assets/942c3d96-b37a-4fa0-b5d0-bce74a1fdac9" alt="Gin" width="500"/>
</div>
<div align="center">
    <H1>OTP and reference ID received from the email.</H1>
    <img src="https://github.com/user-attachments/assets/cf4723ca-4919-4daa-9cf8-a552f6705c01" alt="OTP" width="600"/>
    <H1>An otpauth/TOTP has been generated.</H1>
    <img src="https://github.com/user-attachments/assets/fd173425-7a17-4884-99dc-8edbc5dd2be5" alt="TOTP" width="600"/>
    <H1>There are many libraries available to use an otpauth/TOTP link to generate a QR code for TOTP.</H1>
    <img src="https://github.com/user-attachments/assets/d12b2427-9599-4fe3-a2d1-e51113046d8f" alt="TOTP" width="600"/>
    <H1>Microsoft Authenticator</H1>
    <img src="https://github.com/user-attachments/assets/7cc6caf3-534d-4453-a757-688c8d6383b4" alt="TOTP" width="250"/>
    <H1>Google Authenticator</H1>
    <img src="https://github.com/user-attachments/assets/3ecfd1e0-7d6b-4850-aa72-818aa827c78d" alt="TOTP" width="250"/>
    <H1>Both TOTPs from different authenticators generate the same TOTP number, which can be used for validation within 30 seconds.</H1>
    <img src="https://github.com/user-attachments/assets/ab913ccf-f4e5-45c0-9d6e-227657a4a266" alt="TOTP" width="500"/>
</div>

Golang/Gin-framework database postgresql+pgadmin
