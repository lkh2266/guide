＃安装node.js and discord.js

##安装node.js

要使用discord.js，您需要安装[ node.js ] （https://nodejs.org/ ）的最新LTS版本。

：：： 提示
要检查您的计算机上是否已经安装了节点\（例如，如果使用VPS \），请在终端中运行` node -v` 。建议使用最新的LTS版本的节点。
:::

On Windows, it's as simple as installing any other program. Download the latest version from [the Node.js website](https://nodejs.org/), open the downloaded file, and follow the steps from the installer.

On macOS, either:

- Download the latest version from [the Node.js website](https://nodejs.org/), open the package installer, and follow the instructions
- Use a package manager like [Homebrew](https://brew.sh/) with the command `brew install node`

在Linux上，您可以咨询[此页] （https://nodejs.org/en/download/package-manager/ ），以确定如何安装节点。

##准备必需品

要使用Discord.js，您需要通过NPM \（Node的Package Manager \）安装它。 NPM随附每个节点安装，因此您不必担心安装它。但是，在安装任何内容之前，您应该设置一个新的项目文件夹。

导航到机器上合适的位置，并创建一个名为“ Discord-Bot ”（或您想要的）的新文件夹。接下来，您需要打开终端。

###打开终端

：：： 提示
如果使用[ Visual Studio Code ] （https://code.visualstudio.com/ ），则可以按<code> ctrl +` </ code > （Backtick ）打开其集成的终端。
:::

在Windows上，要么：

-  ` shift +右键单击`在项目目录内，然后选择“打开命令窗口”选项
- Press `Win + R` and run `cmd.exe`, and then `cd` into your project directory

On macOS, either:
- Open Launchpad or Spotlight and search for "Terminal"
- In your "Applications" folder, under "Utilities", open the Terminal app

On Linux, you can quickly open the terminal with `Ctrl + Alt + T`.

With the terminal open, run the `node -v` command to make sure you've successfully installed Node.js.

### Initiating a project folder

:::: code-group
::: code-group-item npm
```sh:no-line-numbers
npm init
```
:::
::: code-group-item yarn
```sh:no-line-numbers
yarn init
```
:::
::: code-group-item pnpm
```sh:no-line-numbers
pnpm init
```
:::
::: code-group-item bun
```sh:no-line-numbers
bun init
```
:::
::::

This is the next command you'll be running. This command creates a `package.json` file for you, which will keep track of the dependencies your project uses, as well as other info.

This command will ask you a sequence of questions–you should fill them out as you see fit. If you're not sure of something or want to skip it as a whole, leave it blank and press enter.

::: tip
To get started quickly, you can run the following command to have it fill out everything for you.

<CodeGroup>
  <CodeGroupItem title="npm">

```sh:no-line-numbers
npm init -y
```

  </CodeGroupItem>
  <CodeGroupItem title="yarn">

```sh:no-line-numbers
yarn init -y
```

  </CodeGroupItem>
  <CodeGroupItem title="pnpm">

```sh:no-line-numbers
pnpm init
```

  </CodeGroupItem>
  <CodeGroupItem title="bun">

```sh:no-line-numbers
bun init -y
```

  </CodeGroupItem>
</CodeGroup>
:::

Once you're done with that, you're ready to install discord.js!

## Installing discord.js

Now that you've installed Node.js and know how to open your console and run commands, you can finally install discord.js! Run the following command in your terminal:

:::: code-group
::: code-group-item npm
```sh:no-line-numbers
npm install discord.js
```
:::
::: code-group-item yarn
```sh:no-line-numbers
yarn add discord.js
```
:::
::: code-group-item pnpm
```sh:no-line-numbers
pnpm add discord.js
```
:::
::: code-group-item bun
```sh:no-line-numbers
bun add discord.js
```
:::
::::

And that's it! With all the necessities installed, you're almost ready to start coding your bot.

## Installing a linter

While you are coding, it's possible to run into numerous syntax errors or code in an inconsistent style. You should [install a linter](/preparations/setting-up-a-linter.md) to ease these troubles. While code editors generally can point out syntax errors, linters coerce your code into a specific style as defined by the configuration. While this is not required, it is advised.
