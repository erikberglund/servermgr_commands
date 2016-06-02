# servermgr_certs

```console
/Applications/Server.app/Contents/ServerRoot/usr/share/servermgrd/bundles/servermgr_certs.bundle/Contents/MacOS/servermgr_certs
```

# Commands

* [acquirePushCertificate](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#acquirepushcertificate)
* [cancelPushCertificate](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#cancelpushcertificate)
* [certificatesNeedingRenewal](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#certificatesneedingrenewal)
* [createCertificateSigningRequest](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#createcertificatesigningrequest)
* [createDefaultSelfSignedIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#createdefaultselfsignedidentity)
* [createInitialPushIdentities](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#createinitialpushidentities)
* [createODSignedIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#createodsignedidentity)
* [createSelfSignedIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#createselfsignedidentity)
* [deleteCertificateSigningRequest](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#deletecertificatesigningrequest)
* [deleteIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#deleteidentity)
* [exportAllIdentities](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#exportallidentities)
* [exportDirectory](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#exportdirectory)
* [exportIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#exportidentity)
* [exportPathsForIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#exportpathsforidentity)
* [fingerprintForIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#fingerprintforidentity)
* [getPushCertificateStatus](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#getpushcertificatestatus)
* [getPushTopicForPreferredIdentityName](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#getpushtopicforpreferredidentityname)
* [getState](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#getstate)
* [importCertificates](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#importcertificates)
* [importIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#importidentity)
* [initialSetup](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#initialsetup)
* [isODCAPresent](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#isodcapresent)
* [migrateLegacyAccess](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#migratelegacyaccess)
* [passphraseForExportedPrivateKey](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#passphraseforexportedprivatekey)
* [readCertificateSigningRequests](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#readcertificatesigningrequests)
* [readDefaultIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#readdefaultidentity)
* [readIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#readidentity)
* [readIdentityCertificates](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#readidentitycertificates)
* [readODIdentities](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#readodidentities)
* [readSettings](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#readsettings)
* [renewIdentity](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#renewidentity)
* [renewPushCertificate](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#renewpushcertificate)
* [sendPushCertificateSigningRequest](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#sendpushcertificatesigningrequest)
* [sendPushEmailConfirmationRequest](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#sendpushemailconfirmationrequest)
* [setState](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#setstate)
* [startIfNeeded](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#startifneeded)
* [updateIdentityWithCertificate](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#updateidentitywithcertificate)
* [validateCertificate](https://github.com/erikberglund/servermgr_commands/blob/master/servermgr_certs.md#validatecertificate)

# Command Descriptions

## acquirePushCertificate

```bash
sudo serveradmin -x command certs:command = acquirePushCertificate
```

## cancelPushCertificate

```bash
sudo serveradmin -x command certs:command = cancelPushCertificate
```

## certificatesNeedingRenewal

```bash
sudo serveradmin -x command certs:command = certificatesNeedingRenewal
```

## createCertificateSigningRequest

```bash
sudo serveradmin -x command certs:command = createCertificateSigningRequest
```

## createDefaultSelfSignedIdentity

```bash
sudo serveradmin -x command certs:command = createDefaultSelfSignedIdentity
```

## createInitialPushIdentities

```bash
sudo serveradmin -x command certs:command = createInitialPushIdentities
```

## createODSignedIdentity

```bash
sudo serveradmin -x command certs:command = createODSignedIdentity
```

## createSelfSignedIdentity

```bash
sudo serveradmin -x command certs:command = createSelfSignedIdentity
```

## deleteCertificateSigningRequest

```bash
sudo serveradmin -x command certs:command = deleteCertificateSigningRequest
```

## deleteIdentity

```bash
sudo serveradmin -x command certs:command = deleteIdentity
```

## exportAllIdentities

```bash
sudo serveradmin -x command certs:command = exportAllIdentities
```

## exportDirectory

```bash
sudo serveradmin -x command certs:command = exportDirectory
```

## exportIdentity

```bash
sudo serveradmin -x command certs:command = exportIdentity
```

## exportPathsForIdentity

```bash
sudo serveradmin -x command certs:command = exportPathsForIdentity
```

## fingerprintForIdentity

```bash
sudo serveradmin -x command certs:command = fingerprintForIdentity
```

## getPushCertificateStatus

```bash
sudo serveradmin -x command certs:command = getPushCertificateStatus
```

## getPushTopicForPreferredIdentityName

```bash
sudo serveradmin -x command certs:command = getPushTopicForPreferredIdentityName
```

## getState

```bash
sudo serveradmin -x command certs:command = getState
```

## importCertificates

```bash
sudo serveradmin -x command certs:command = importCertificates
```

## importIdentity

```bash
sudo serveradmin -x command certs:command = importIdentity
```

## initialSetup

```bash
sudo serveradmin -x command certs:command = initialSetup
```

## isODCAPresent

```bash
sudo serveradmin -x command certs:command = isODCAPresent
```

## migrateLegacyAccess

```bash
sudo serveradmin -x command certs:command = migrateLegacyAccess
```

## passphraseForExportedPrivateKey

```bash
sudo serveradmin -x command certs:command = passphraseForExportedPrivateKey
```

## readCertificateSigningRequests

```bash
sudo serveradmin -x command certs:command = readCertificateSigningRequests
```

## readDefaultIdentity

```bash
sudo serveradmin -x command certs:command = readDefaultIdentity
```

## readIdentity

```bash
sudo serveradmin -x command certs:command = readIdentity
```

## readIdentityCertificates

```bash
sudo serveradmin -x command certs:command = readIdentityCertificates
```

## readODIdentities

```bash
sudo serveradmin -x command certs:command = readODIdentities
```

## readSettings

```bash
sudo serveradmin -x command certs:command = readSettings
```

## renewIdentity

```bash
sudo serveradmin -x command certs:command = renewIdentity
```

## renewPushCertificate

```bash
sudo serveradmin -x command certs:command = renewPushCertificate
```

## sendPushCertificateSigningRequest

```bash
sudo serveradmin -x command certs:command = sendPushCertificateSigningRequest
```

## sendPushEmailConfirmationRequest

```bash
sudo serveradmin -x command certs:command = sendPushEmailConfirmationRequest
```

## setState

```bash
sudo serveradmin -x command certs:command = setState
```

## startIfNeeded

```bash
sudo serveradmin -x command certs:command = startIfNeeded
```

## updateIdentityWithCertificate

```bash
sudo serveradmin -x command certs:command = updateIdentityWithCertificate
```

## validateCertificate

```bash
sudo serveradmin -x command certs:command = validateCertificate
```

