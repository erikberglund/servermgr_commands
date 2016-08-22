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

**Availability**
* 5.1.7-15S7055

## cancelPushCertificate

```bash
sudo serveradmin -x command certs:command = cancelPushCertificate
```

**Availability**
* 5.1.7-15S7055

## certificatesNeedingRenewal

```bash
sudo serveradmin -x command certs:command = certificatesNeedingRenewal
```

**Availability**
* 5.1.7-15S7055

## createCertificateSigningRequest

```bash
sudo serveradmin -x command certs:command = createCertificateSigningRequest
```

**Availability**
* 5.1.7-15S7055

## createDefaultSelfSignedIdentity

```bash
sudo serveradmin -x command certs:command = createDefaultSelfSignedIdentity
```

**Availability**
* 5.1.7-15S7055

## createInitialPushIdentities

```bash
sudo serveradmin -x command certs:command = createInitialPushIdentities
```

**Availability**
* 5.1.7-15S7055

## createODSignedIdentity

```bash
sudo serveradmin -x command certs:command = createODSignedIdentity
```

**Availability**
* 5.1.7-15S7055

## createSelfSignedIdentity

```bash
sudo serveradmin -x command certs:command = createSelfSignedIdentity
```

**Availability**
* 5.1.7-15S7055

## deleteCertificateSigningRequest

```bash
sudo serveradmin -x command certs:command = deleteCertificateSigningRequest
```

**Availability**
* 5.1.7-15S7055

## deleteIdentity

```bash
sudo serveradmin -x command certs:command = deleteIdentity
```

**Availability**
* 5.1.7-15S7055

## exportAllIdentities

```bash
sudo serveradmin -x command certs:command = exportAllIdentities
```

**Availability**
* 5.1.7-15S7055

## exportDirectory

```bash
sudo serveradmin -x command certs:command = exportDirectory
```

**Availability**
* 5.1.7-15S7055

## exportIdentity

```bash
sudo serveradmin -x command certs:command = exportIdentity
```

**Availability**
* 5.1.7-15S7055

## exportPathsForIdentity

```bash
sudo serveradmin -x command certs:command = exportPathsForIdentity
```

**Availability**
* 5.1.7-15S7055

## fingerprintForIdentity

```bash
sudo serveradmin -x command certs:command = fingerprintForIdentity
```

**Availability**
* 5.1.7-15S7055

## getPushCertificateStatus

```bash
sudo serveradmin -x command certs:command = getPushCertificateStatus
```

**Availability**
* 5.1.7-15S7055

## getPushTopicForPreferredIdentityName

```bash
sudo serveradmin -x command certs:command = getPushTopicForPreferredIdentityName
```

**Availability**
* 5.1.7-15S7055

## getState

```bash
sudo serveradmin -x command certs:command = getState
```

**Availability**
* 5.1.7-15S7055

## importCertificates

```bash
sudo serveradmin -x command certs:command = importCertificates
```

**Availability**
* 5.1.7-15S7055

## importIdentity

```bash
sudo serveradmin -x command certs:command = importIdentity
```

**Availability**
* 5.1.7-15S7055

## initialSetup

```bash
sudo serveradmin -x command certs:command = initialSetup
```

**Availability**
* 5.1.7-15S7055

## isODCAPresent

```bash
sudo serveradmin -x command certs:command = isODCAPresent
```

**Availability**
* 5.1.7-15S7055

## migrateLegacyAccess

```bash
sudo serveradmin -x command certs:command = migrateLegacyAccess
```

**Availability**
* 5.1.7-15S7055

## passphraseForExportedPrivateKey

```bash
sudo serveradmin -x command certs:command = passphraseForExportedPrivateKey
```

**Availability**
* 5.1.7-15S7055

## readCertificateSigningRequests

```bash
sudo serveradmin -x command certs:command = readCertificateSigningRequests
```

**Availability**
* 5.1.7-15S7055

## readDefaultIdentity

```bash
sudo serveradmin -x command certs:command = readDefaultIdentity
```

**Availability**
* 5.1.7-15S7055

## readIdentity

```bash
sudo serveradmin -x command certs:command = readIdentity
```

**Availability**
* 5.1.7-15S7055

## readIdentityCertificates

```bash
sudo serveradmin -x command certs:command = readIdentityCertificates
```

**Availability**
* 5.1.7-15S7055

## readODIdentities

```bash
sudo serveradmin -x command certs:command = readODIdentities
```

**Availability**
* 5.1.7-15S7055

## readSettings

```bash
sudo serveradmin -x command certs:command = readSettings
```

**Availability**
* 5.1.7-15S7055

## renewIdentity

```bash
sudo serveradmin -x command certs:command = renewIdentity
```

**Availability**
* 5.1.7-15S7055

## renewPushCertificate

```bash
sudo serveradmin -x command certs:command = renewPushCertificate
```

**Availability**
* 5.1.7-15S7055

## sendPushCertificateSigningRequest

```bash
sudo serveradmin -x command certs:command = sendPushCertificateSigningRequest
```

**Availability**
* 5.1.7-15S7055

## sendPushEmailConfirmationRequest

```bash
sudo serveradmin -x command certs:command = sendPushEmailConfirmationRequest
```

**Availability**
* 5.1.7-15S7055

## setState

```bash
sudo serveradmin -x command certs:command = setState
```

**Availability**
* 5.1.7-15S7055

## startIfNeeded

```bash
sudo serveradmin -x command certs:command = startIfNeeded
```

**Availability**
* 5.1.7-15S7055

## updateIdentityWithCertificate

```bash
sudo serveradmin -x command certs:command = updateIdentityWithCertificate
```

**Availability**
* 5.1.7-15S7055

## validateCertificate

```bash
sudo serveradmin -x command certs:command = validateCertificate
```

**Availability**
* 5.1.7-15S7055

