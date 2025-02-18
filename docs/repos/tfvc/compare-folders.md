---
title: Compare folders
titleSuffix: Azure Repos
description: Compare folders
ms.assetid: 9c894c51-c34c-4c03-a840-5e485dbbc55d
ms.technology: devops-code-tfvc
ms.topic: conceptual
ms.date: 12/17/2021
monikerRange: '<= azure-devops'
---


# Compare folders

[!INCLUDE [temp](../includes/version-tfs-2013-cloud.md)]
[!INCLUDE [temp](../includes/version-vs-2013-vs-2019.md)]

You can compare the differences between two server folders, two local folders, or a server folder and a local folder.

## Prerequisites  

To perform these procedures, you must have the **Read** permission set to **Allow**. For more information, see [Default TFVC permissions](../../organizations/security/default-tfvc-permissions.md).

> [!NOTE]
> To compare two local folders, you do not need any Azure DevOps permissions.

### To compare folders by using Folder Difference

1.  On the **View** menu, choose **Other Windows**, and then choose **Source Control Explorer**.

2.  In **Source Control Explorer**, locate the source folder you want to compare, open its shortcut menu, and then choose **Compare**.

    The **Compare** dialog box appears and the version control path of the folder that you selected is in the **Source Path** box.

3.  Under **Source Version**, select the **Type** you want to use for comparison: **Changeset**, **Date**, **Label**, **Latest Version**, or **Workspace Version**.

4.  Enter the **Target Path** or choose **Browse** and locate the target folder.

5.  If the **Target Path** is to a server folder, under **Target Version**, select the **Type** you want to use for comparison: **Changeset**, **Date**, **Label**, **Latest Version**, or **Workspace Version**.

6.  Under **Filter**, you can add or remove file and folder filters.

    For more information, see [Folder comparison filters](folder-comparison-filters.md).

    Select the **Filter local paths only** box if you want to apply the filter only to local paths.

7.  Under **View Options**, select which items that you want shown in the comparison results. You can select a combination of view options by checking or clearing the following boxes:  
    -   **Show items that exist only in source path**.  
    -   **Show items that exist only in target path**.  
    -   **Show items that are different**.  
    -   **Show items that are the same**.

8.  Choose **OK**.

    The **Folder Difference** window displays a list of items that are compared in the source and target folders.

    -   You can compare the differences between two versions of a file by opening its shortcut menu and choosing **Compare**. The [Diff window](compare-files.md) appears.  
    -   If there are differences between a server folder and your local folder, you can [reconcile them](reconcile-differences-between-two-folders.md).

## Related articles

-  [Folder comparison filters](folder-comparison-filters.md)  
-  [Compare files](compare-files.md)  
-  [Reconcile differences between two folders](reconcile-differences-between-two-folders.md) 
