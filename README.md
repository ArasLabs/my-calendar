# My Calendar

This project displays the InBasket contents in monthly calendar notation, with workflow tasks and project tasks displayed in different colors. Also, similarly to "In Basket", only tasks assigned to the logged in user are displayed.

* ステータスや、コンテナ情報などで条件の絞り込みを行ったり、表示順を変更したりとAras Innovatorの標準で実装されている機能ですが、ことらをもう少し視覚的に表現できる機能を「My Calendar」として実装しています。
* 月単位のカレンダー表記で表示され、①ワークフロータスク、②プロジェクトタスクが視覚的に判りやすく、色分けされて表示されます。また、「In Basket」同様に、ログイン者がアサインされているタスクのみ表示されます。

## History

This project and the following release notes have been migrated from the old Aras Projects page.

Release | Notes
--------|--------
[v11SP5](https://github.com/ArasLabs/my-calendar/releases/tag/v11SP5) | Support version 11SP5. Instructions are described in the ReadMe.pdf.

#### Supported Aras Versions

Project | Aras
--------|------
[v11SP5](https://github.com/ArasLabs/my-calendar/releases/tag/v11SP5) | 11.0 SP5

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **MyCalendar** import package

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\MyCalendar\Import\imports.mf` file in the Manifest File field.
6. Select **MyCalendar** in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Usage

Review the [ReadMe-MyCalendar.pdf](./Documentation/ReadMe-MyCalendar.pdf) for information on using the project. {[English translation](./Documentation/ReadMe-MyCalendar-English.docx)}

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

Created by NEOSYSTEM Co., Ltd.
