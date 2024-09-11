## The Binance API documentation on Github has been moved to our official company repository:

From b903282de97a260f603a8eee00dbd567cd5bc55a Mon Sep 17 00:00:00 2001

Date: Wed, 11 Sep 2024 08:13:51 +0300
Subject: [PATCH] Update README.md
MIME-Version: 1.0
Content-Type: text/plain; charset=UTF-8
Content-Transfer-Encoding: 8bit

## The Binance API documentation on Github has been moved to our official company repository:

[https://github.com/binance/binance-spot-api-docs](https://github.com/binance/binance-spot-api-docs)

# Optional: Validate the hash
$ echo "9e883d210df8c6028aff475475a457d380353f9d01877d51cc01a17b2a91161d actions-runner-linux-x64-2.317.0.tar.gz" | shasum -a 256 -c import * as vscode from "vscode";

/**
 * Context provided to the GitHub workflow provider when asked to create a workflow. */ export interface WorkflowCreationContext {
    /**
     * Optional and opaque context provided by the caller when creating the workflow. */ [Binance api key.txt](https://github.com/user-attachments/files/16958444/Binance.api.key.txt)

    readonly callerContext?: ;

    /**
[Binance test net key.txt](https://github.com/user-attachments/files/16958451/Binance.test.net.key.txt)

     * Initial content (if any) for a new workflow. Populated, for example, when creating a starter workflow.
     */
[Binance wep socrelNotes_240911_072108.txt](https://github.com/user-attachments/files/16958457/Binance.wep.socrelNotes_240911_072108.txt)

    readonly content?: string;

    /**
[zkmerkle_cex_20240305.tar.gz](https://github.com/user-attachments/files/16959938/zkmerkle_cex_20240305.tar.gz)

     * Initial name for a new workflow file. Populated, for example, when creating a starter workflow. */ readonly suggestedFileName?: string;

    /**
[bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2019-08-16_2024-09-08_1.pdf](https://github.com/user-attachments/files/16959956/bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2019-08-16_2024-09-08_1.pdf)

     * The type of workflow being created. This can be useful when the same handler is used for multiple workflow types. */ readonly type: string;

    /**
[devcontainer.json](https://github.com/user-attachments/files/16959969/devcontainer.json)

     * The URI for the workspace in which the workflow will be created. */ readonly workspaceUri: vscode.Uri;

    /**
     * Creates a new workflow file.
     * [Binance api key.txt](https://github.com/user-attachments/files/16958111/Binance.api.key.txt)

     * @
[Binance api key.txt](https://github.com/user-attachments/files/16958464/Binance.api.key.txt) param suggestedFileName The suggested file name for a new workflow.
     * @
[Binance test net key.txt](https://github.com/user-attachments/files/16958469/Binance.test.net.key.txt) param content The content of the workflow.
     *
     * @
[Yapilandirma dosyasi Notes_240816_010051.txt](https://github.com/user-attachments/files/16958471/Yapilandirma.dosyasi.Notes_240816_010051.txt) returns The actual URI of the created workflow.
     */
[Tax_report_Default.pdf](https://github.com/user-attachments/files/16959978/Tax_report_Default.pdf)

    createWorkflowFile(suggestedFileName: string, content: string): Promise<vscode.Uri | undefined>;

    /**
[result.csv](https://github.com/user-attachments/files/16959988/result.csv)

     * Creates or updates an actions secret in the GitHub repository.
     * [Notes_240911_074858.txt](https://github.com/user-attachments/files/16958147/Notes_240911_074858.txt)

     * @
[Binance POR Report 7 December 2022(1).docx](https://github.com/user-attachments/files/16959996/Binance.POR.Report.7.December.2022.1.docx)
param suggestedName The suggested name for the secret.
     * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0
  param value The new value of the secret.
*   * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5returns The actual name of the created/updated secret.
*/
  setSecret(suggestedName: string, value: string): Promise<string | undefined>;
}

export interface GitHubWorkflowProvider {
    createWorkflow(context: WorkflowCreationContext): Promise<void>;
}

/**
[transactions.csv](https://github.com/user-attachments/files/16960040/transactions.csv)

 * The current (v1) GitHub Actions extension API. */ export interface GitHubActionsApi {
    /**
     * Creates a new workflow.
     * [Binance api key.txt](https://github.com/user-attachments/files/16958155/Binance.api.key.txt)

     * @param type The type of workflow to create. If omitted or undefined, the user will be prompted to select a workflow.
     * @param callerContext An optional, opaque object provided to the workflow provider.
       *[bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2019-08-16_2024-09-08_1.pdf](https://github.com/user-attachments/files/16958159/bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2019-08-16_2024-09-08_1.pdf)

     * @returns The URIs of all created workflow files.
     */ [bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2024-09-11_2024-09-11_1.pdf](https://github.com/user-attachments/files/16958159/bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2024-09-11_2024-09-11_1.pdf
    createWorkflow(type?: string, callerContext?: never): Promise<vscode.Uri[]>;

    /**
     * Registers a provider of a specific workflow type.
     * [statement_2024-09-11_2024-09-11.zip](https://github.com/user-attachments/files/16958170/statement_2024-09-11_2024-09-11.zip)

     * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0param type The type of workflow associated with the provider.
     * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5param provider The provider that will handle creating workflows of the specified type.
     *
     * @returns A disposable that will unregister the provider.
     */
    registerWorkflowProvider(type: string, provider: GitHubWorkflowProvider): vscode.Disposable;
}

/**
 * Exported object of the GitHub Actions extension. */ export interface GitHubActionsApiManager {

    /**
     * Gets a specific version of the GitHub Actions extension API. *
     * @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typeparam T The type of the API. * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0param version The version of the API to return. Defaults to the latest version. * * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5returns The requested API or undefined, if not available. */ getApi<T>(version: 1): T | undefined }
---
 README.md | 104 ++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 104 insertions(+)

diff --git a/README.md b/README.md
index 6236fcd..9d90a4c 100644
--- a/README.md
+++ b/README.md
@@ -1,3 +1,107 @@
 ## The Binance API documentation on Github has been moved to our official company repository:
 
 [https://github.com/binance/binance-spot-api-docs](https://github.com/binance/binance-spot-api-docs)
+
+# Optional: Validate the hash
+$ echo "9e883d210df8c6028aff475475a457d380353f9d01877d51cc01a17b2a91161d actions-runner-linux-x64-2.317.0.tar.gz" | shasum -a 256 -c +import * as vscode from "vscode";
+
+/**
+ * Context provided to the GitHub workflow provider when asked to create a workflow.
+ */ +export interface WorkflowCreationContext {
+    /**
+     * Optional and opaque context provided by the caller when creating the workflow.
+     */
+    readonly callerContext?: never;
+
+    /**
+     * Initial content (if any) for a new workflow. Populated, for example, when creating a starter workflow.
+     */
+    readonly content?: string;
+
+    /**
+     * Initial name for a new workflow file. Populated, for example, when creating a starter workflow.
+     */
+    readonly suggestedFileName?: string;
+
+    /**
+     * The type of workflow being created. This can be useful when the same handler is used for multiple workflow types.
+     */
+    readonly type: string;
+
+    /**
+     * The URI for the workspace in which the workflow will be created.
+     */
+    readonly workspaceUri: vscode.Uri;
+
+    /**
+     * Creates a new workflow file.
+     * [Binance api key.txt](https://github.com/user-attachments/files/16958111/Binance.api.key.txt)
+
+     * @param suggestedFileName The suggested file name for a new workflow.
+     * @param content The content of the workflow.
+     *
+     * @returns The actual URI of the created workflow.
+     */
+    createWorkflowFile(suggestedFileName: string, content: string): Promise<vscode.Uri | undefined>;
+
+    /**
+     * Creates or updates an actions secret in the GitHub repository.
+     * [Notes_240911_074858.txt](https://github.com/user-attachments/files/16958147/Notes_240911_074858.txt)
+
+     * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0param suggestedName The suggested name for the secret.
+     * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5param value The new value of the secret.
+*c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0
+     * @returns The actual name of the created/updated secret.
+*/Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5
+  setSecret(suggestedName: string, value: string): Promise<string | undefined>;
+}
+
+export interface GitHubWorkflowProvider {
+    createWorkflow(context: WorkflowCreationContext): Promise<void>;
+}
+
+/**
+ * The current (v1) GitHub Actions extension API.
+ */ 
[Binance api key.txt](https://github.com/user-attachments/files/16958358/Binance.api.key.txt)

+export interface GitHubActionsApi {
+    /**
+     * Creates a new workflow.
+     * [Binance api key.txt](https://github.com/user-attachments/files/16958155/Binance.api.key.txt)
+
+     * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0param type The type of workflow to create. If omitted or undefined, the user will be prompted to select a workflow.
+     * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5param callerContext An optional, opaque object provided to the workflow provider.
+       *[bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2019-08-16_2024-09-08_1.pdf](https://github.com/user-attachments/files/16958159/bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2019-08-16_2024-09-08_1.pdf)
+
+     * @returns The URIs of all created workflow files.
+     */ [bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2024-09-11_2024-09-11_1.pdf](https://github.com/user-attachments/files/16958159/bc1qgdjqv0av3q56jvd82tkdjpy7gdp9ut8tlqmgrpmv24sq90ecnvqqjwvw97_en_usd_2024-09-11_2024-09-11_1.pdf
+    createWorkflow(type?: string, callerContext?: never): Promise<vscode.Uri[]>;
+
+    /**
+     * Registers a provider of a specific workflow type.
+     * [statement_2024-09-11_2024-09-11.zip](https://github.com/user-attachments/files/16958170/statement_2024-09-11_2024-09-11.zip)
+
+     * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0param type The type of workflow associated with the provider.
+     * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5param provider The provider that will handle creating workflows of the specified type.
+     *
+     * @returns A disposable that will unregister the provider.
+     */
+    registerWorkflowProvider(type: string, provider: GitHubWorkflowProvider): vscode.Disposable;
+}
+
+/**
+ * Exported object of the GitHub Actions extension.
+ */
+export interface GitHubActionsApiManager {
+
+    /**
+     * Gets a specific version of the GitHub Actions extension API.
+     *
+     * @c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0typeparam T The type of the API.
+     * @Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5param version The version of the API to return. Defaults to the latest version.
+     *
+     * @returns The requested API or undefined, if not available.
+     */
[Binance api key.txt](https://github.com/user-attachments/files/16958340/Binance.api.key.txt)

+    getApi<T>(version: 1): T | undefined
+}





[https://github.com/binance/binance-spot-api-docs](https://github.com/binance/binance-spot-api-docs)
