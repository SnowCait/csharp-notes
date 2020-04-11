# AWS Lambda

using .NET Core 3.1;

## Official
- [aws/aws-lambda-dotnet: Libraries, samples and tools to help .NET Core developers develop AWS Lambda functions.](https://github.com/aws/aws-lambda-dotnet)
- [AWS Lambda が .NET Core 3.1 のサポートを開始](https://aws.amazon.com/jp/about-aws/whats-new/2020/03/aws-lambda-now-supports-net-core-3-1/)
  - [Announcing AWS Lambda support for .NET Core 3.1 | AWS Compute Blog](https://aws.amazon.com/jp/blogs/compute/announcing-aws-lambda-supports-for-net-core-3-1/)
- [Building Lambda Functions with C# - AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/lambda-csharp.html)

## Document
- Working with C#
  - Deployment Package
    - .NET Core CLI
    - [AWS Toolkit for Visual Studio](#aws-toolkit-for-visual-studio)
  - Handler
  - Context
  - Logging
  - Errors

### [AWS Toolkit for Visual Studio](https://docs.aws.amazon.com/lambda/latest/dg/csharp-package-toolkit.html)
You can build .NET-based Lambda applications using the Lambda plugin to the AWS Toolkit for Visual Studio. The toolkit is available as a Visual Studio extension.

1. Microsoft Visual Studio を起動して **新しいプロジェクト** を選択します。  
  a. **ファイル** メニューから **新規作成** を選択して **プロジェクト** を選択します。  
  b. **新しいプロジェクトの作成** ウィンドウで **AWS Lambda Project (.NET Core)** を選択して **次へ** を選択します。  
  c. **Select Blueprint** ウィンドウで you will be presented with the option of selecting from a list of sample applications that will provide you with sample code to get started with creating a .NET-based Lambda application.  
  d. スクラッチで Lambda アプリケーションを作成する場合は **Empty Function** を選択して **Finishi** を選択します。  
  
