# Role

{% hint style="info" %}
A single role, which can be assigned to create a permission for a specific entity.
{% endhint %}

## Properties <a href="#properties" id="properties"></a>

| Name          | Type           | Description                                                           |
| ------------- | -------------- | --------------------------------------------------------------------- |
| `appAddress`  | `String`       | Address of the app this role belongs to.                              |
| `description` | `String`       | Description of the role. E.g. `"Mint tokens"`.                        |
| `permissions` | `Permission[]` | Permissions associated to the role.                                   |
| `hash`        | `String`       | Encoded identifier for the role.                                      |
| `name`        | `String`       | Identifier of the role. E.g. `"MINT_ROLE"`.                           |
| `manager`     | `String`       | Address of the role manager.                                          |
| `params`      | `String[]`     | Params associated to the role. E.g. `[ "Receiver", "Token amount" ]`. |
