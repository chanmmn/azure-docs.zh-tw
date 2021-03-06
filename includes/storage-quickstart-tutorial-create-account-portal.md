## <a name="create-a-storage-account-using-the-azure-portal"></a>使用 Azure 入口網站建立儲存體帳戶

首先，建立新的一般用途儲存體帳戶供本快速入門使用。 

1. 使用您的 Azure 帳戶登入 [Azure 入口網站](https://portal.azure.com)。 
2. 在 [中樞] 功能表上，選取 [新增] > [儲存體] > [儲存體帳戶- Blob、檔案、資料表、佇列]。 
3. 輸入儲存體帳戶的唯一名稱。 為您的儲存體帳戶命名時，請記住這些規則：
    - 名稱長度必須介於 3 到 24 個字元之間。
    - 名稱僅能包含數字和小寫字母。
4. 確定已設定下列預設值： 
    - [部署模型] 設為 **Resource manager**。
    - [帳戶種類] 設為 [一般用途]。
    - [效能] 設為 [標準]。
    - [複寫] 設為 [本地備援儲存體 (LRS)]。
5. 選取您的訂用帳戶。 
6. 若為**資源群組**，請建立一個新的資源群組並提供它唯一的名稱。 
7. 選取 [位置] 供儲存體帳戶使用。
8. 核取 [釘選到儀表板] 並按一下 [建立] 以建立儲存體帳戶。 

儲存體帳戶建立之後，就會釘選到儀表板。 按一下開啟它。 按一下 [設定] 下的 [存取金鑰]。 選取主要金鑰，並將相關聯的**連接字串**複製到剪貼簿，然後貼到 [文字編輯器] 供日後使用。
