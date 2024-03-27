# [Command] _netappfiles volume delete_

Delete the specified volume

## Versions

### [2022-11-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXRhcHAvbmV0YXBwYWNjb3VudHMve30vY2FwYWNpdHlwb29scy97fS92b2x1bWVzL3t9/2022-11-01-preview.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.netapp/netappaccounts/{}/capacitypools/{}/volumes/{} 2022-11-01-preview -->

### [2023-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXRhcHAvbmV0YXBwYWNjb3VudHMve30vY2FwYWNpdHlwb29scy97fS92b2x1bWVzL3t9/2023-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.netapp/netappaccounts/{}/capacitypools/{}/volumes/{} 2023-05-01 -->

#### examples

- Delete an ANF volume
    ```bash
        netappfiles volume delete -g mygroup --account-name myaccname --pool-name mypoolname --name myvolname
    ```

### [2023-05-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXRhcHAvbmV0YXBwYWNjb3VudHMve30vY2FwYWNpdHlwb29scy97fS92b2x1bWVzL3t9/2023-05-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.netapp/netappaccounts/{}/capacitypools/{}/volumes/{} 2023-05-01-preview -->

#### examples

- Delete an ANF volume
    ```bash
        netappfiles volume delete -g mygroup --account-name myaccname --pool-name mypoolname --name myvolname
    ```