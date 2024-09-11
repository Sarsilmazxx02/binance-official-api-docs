## The Binance API documentation on Github has been moved to our official company repository:

[https://github.com/binance/binance-spot-api-docs](https://github.com/binance/binance-spot-api-docs)

# Optional: Validate the hash
$ echo "9e883d210df8c6028aff475475a457d380353f9d01877d51cc01a17b2a91161d actions-runner-linux-x64-2.317.0.tar.gz" | shasum -a 256 -c
import * as vscode from "vscode";

/**
 * Context provided to the GitHub workflow provider when asked to create a workflow.
 */
export interface WorkflowCreationContext {
    /**
     * Optional and opaque context provided by the caller when creating the workflow.
     */
    readonly callerContext?: never;

    /**
     * Initial content (if any) for a new workflow. Populated, for example, when creating a starter workflow.
     */
    readonly content?: string;

    /**
     * Initial name for a new workflow file. Populated, for example, when creating a starter workflow.
     */
    readonly suggestedFileName?: string;

    /**
     * The type of workflow being created. This can be useful when the same handler is used for multiple workflow types.
     */
    readonly type: string;

    /**
     * The URI for the workspace in which the workflow will be created.
     */
    readonly workspaceUri: vscode.Uri;

    /**
     * Creates a new workflow file.
     * [Binance api key.txt](https://github.com/user-attachments/files/16958111/Binance.api.key.txt)

     * @param suggestedFileName The suggested file name for a new workflow.
     * @param content The content of the workflow.
     *
     * @returns The actual URI of the created workflow.
     */
    createWorkflowFile(suggestedFileName: string, content: string): Promise<vscode.Uri | undefined>;

    /**
     * Creates or updates an actions secret in the GitHub repository.
     * [Notes_240911_074858.txt](https://github.com/user-attachments/files/16958147/Notes_240911_074858.txt)

     * @param suggestedName The suggested name for the secret.
     * @param value The new value of the secret.
*c9f3tCe0l34EUaaPSiL9s0KtyRC4mDG0rK4KRPTdxiqhjrCrbgZeTibcexLLApP0
     * @returns The actual name of the created/updated secret.
*/Cittld17y7ynFYzy7NeexmVy0uzLV23OOS1JHFKfz95X1aLFP7Vv75gmCSqmGqL5
  setSecret(suggestedName: string, value: string): Promise<string | undefined>;
}

export interface GitHubWorkflowProvider {
    createWorkflow(context: WorkflowCreationContext): Promise<void>;
}

/**
 * The current (v1) GitHub Actions extension API.
 */
export interface GitHubActionsApi {
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

     * @param type The type of workflow associated with the provider.
     * @param provider The provider that will handle creating workflows of the specified type.
     *
     * @returns A disposable that will unregister the provider.
     */
    registerWorkflowProvider(type: string, provider: GitHubWorkflowProvider): vscode.Disposable;
}

/**
 * Exported object of the GitHub Actions extension.
 */
export interface GitHubActionsApiManager {

    /**
     * Gets a specific version of the GitHub Actions extension API.
     *
     * @typeparam T The type of the API.
     * @param version The version of the API to return. Defaults to the latest version.
     *
     * @returns The requested API or undefined, if not available.
     */
    getApi<T>(version: 1): T | undefined
}
