1. 单击 **Remove（删除）**。
1. 您将看到删除自托管运行器的说明。 完成以下任一步骤来删除运行器，具体取决于它是否仍然可以访问：

    * **如果您可以访问运行器机器：**按照您机器操作系统的屏幕说明运行删除命令。 该说明包括必需的 URL 和一个自动生成的有时限的令牌。

        删除命令执行以下任务：

        * 从 {% data variables.product.product_name %} 删除运行器。
        * 删除机器上的任何自托管运行器应用程序配置文件。
        * 如果未在交互模式下运行，删除配置的任何服务。

    * **如果无法访问该机器**，请单击 **Force remove this runner（强制删除此运行器）**以强制 {% data variables.product.product_name %} 删除运行器。
