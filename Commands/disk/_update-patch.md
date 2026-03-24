# [Command] _disk update-patch_

Update a managed disk.

## Versions

### [2023-04-02](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb21wdXRlL2Rpc2tzL3t9/2023-04-02.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.compute/disks/{} 2023-04-02 -->

#### examples

- Update a managed disk and associate it with a disk access resource.
    ```bash
        disk update --name MyManagedDisk --resource-group MyResourceGroup --network-access-policy AllowPrivate --disk-access MyDiskAccessID
    ```

- Update a managed disk.
    ```bash
        disk update --name MyManagedDisk --resource-group MyResourceGroup --size-gb 20
    ```
