---
-api-id: M:Windows.Networking.NetworkOperators.ESimProfileMetadata.PostponeInstallAsync
-api-type: winrt method
---

<!-- Method syntax.
public IAsyncOperation<ESimOperationResult> ESimProfileMetadata.PostponeInstallAsync()
-->

# Windows.Networking.NetworkOperators.ESimProfileMetadata.PostponeInstallAsync

## -description
Asynchronously postpones the installation of an eSIM profile.

> [!NOTE]
> This functionality is only available to mobile operator apps and UWP apps given privileged access by mobile network operators.
>
> If you want to use this API and publish your app to the Store then you will need to request special approval to use the restricted capability **Microsoft.eSIMManagement_8wekyb3d8bbwe**. For more info, see [Special and restricted capabilities](/windows/uwp/packaging/app-capability-declarations#special-and-restricted-capabilities).

## -returns

## -remarks
An eSIM profile whose installation has been postponed is still reserved at the profile server. You can choose not to process the result of this asynchronous operation, since its purpose is to postpone installation. But an error can be the result of a timeout or a bad connection with the profile server. Any such error condition will effectively postpone the install.

## -see-also

## -examples

## -capabilities
Microsoft.eSIMManagement_8wekyb3d8bbwe