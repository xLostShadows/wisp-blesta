# Fork of the Blesta WiSP module. Made compatible for hosts not using External IDs, or instances where the WiSP API Call does not return the Blesta client's full client ID.

# WiSP Module

This is a module for Blesta that integrates with [WiSP](https://wisp.gg/).

## Install the Module

1. Upload the source code to a /components/modules/wisp/ directory within
your Blesta installation path.

    For example:

    ```
    /var/www/html/blesta/components/modules/wisp/
    ```

3. Log in to your admin Blesta account and navigate to
> Settings > Modules

4. Find the WiSP module and click the "Install" button to install it

5. Add a server with your WiSP credentials

6. You're done!

### Blesta Compatibility

|Blesta Version|Module Version|
|--------------|--------------|
|>= v5.6.1|v1.1.0|
