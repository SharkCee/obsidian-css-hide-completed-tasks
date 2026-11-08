<div align="center">
  
<br><b>✅ Easily hide completed tasks in Obsidian</b></br>
<br>[💡 About](#-about)&nbsp;&nbsp;•&nbsp;&nbsp;[🌱 Getting Started](#-getting-started)&nbsp;&nbsp;•&nbsp;&nbsp;[🔧 Usage](#-usage)&nbsp;&nbsp;•&nbsp;&nbsp;[💭 Property Differences](#-property-differences)
<br>[🫂 Contributing](#-contributing)&nbsp;&nbsp;•&nbsp;&nbsp;[📃 License](#-license)&nbsp;&nbsp;•&nbsp;&nbsp;[🦈 Support Me](#-support-me)</br>
  
<br>![Release](https://img.shields.io/badge/Release-1.0.0-5BCEFA?style=for-the-badge&labelColor=555555&logo=github)&nbsp;&nbsp;&nbsp;![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/sharkcee/obsidian-css-hide-completed-tasks/total?style=for-the-badge&labelColor=E05780)
&nbsp;&nbsp;&nbsp;![GitHub Repo stars](https://img.shields.io/github/stars/sharkcee/obsidian-css-hide-completed-tasks?style=for-the-badge&labelColor=FFFFFF)&nbsp;&nbsp;&nbsp;![license](https://img.shields.io/badge/license-MIT-E05780?style=for-the-badge&labelColor=555555)&nbsp;&nbsp;&nbsp;![Powered By](https://img.shields.io/badge/Powered%20By-Audhd%2C%20idk-5BCEFA?style=for-the-badge&labelColor=555555)
</br>

<hr>

</div>

## 💡 About

<p>This repository has been created to share in a more accessible manner one of my (<i>subjectively</i>) helpful CSS snippets, for other <a href="https://obsidian.md/download">Obsidian</a> users.</p>
<p>It's just a little CSS snippet that's helped me while building my own vault(s), because sometimes it's nicer to keep things clean? I don't know girl, my AuDHD brain hyperfixated on the need to hide completed tasks. 🤷‍♀️</p>
<p><b>Disclaimer:</b> This work is 100% human made.</p>

## 🌱 Getting Started

1. Either download the .css file from the <a href="https://github.com/SharkCee/obsidian-css-hide-completed-tasks/tree/main/CSS">CSS Folder</a>, or clone this repository.
2. Copy the .css file into your vault's <a href="https://obsidian.md/help/configuration-folder">.obsidian folder</a>, in `~/.obsidian/snippets`.
3. Launch Obsidian and open your Vault.
4. Access the <b><a href="https://obsidian.md/help/settings">Settings</a></b> menu.
5. Under <b>Options</b>, select <b>Appearance</b> and then <b>CSS snippets</b>.
6. From <b>CSS snippets</b>, you should see <u>an additional entry</u>[^1]: "<i>Hide Completed Tasks</i>".
7. Enable it by ensuring the toggle is in the correct position.

## 🔧 Usage

After following the steps from [💡 About](#-about), to use this .css snippet, all you need to do is:

1. Open <u>a note</u>[^2] in your vault.
2. Add or open its <a href="https://obsidian.md/help/properties">Properties</a>.
3. Add to the "<i>cssclasses</i>" Property the value of <u>"<i>hide_completed_tasks</i>"</u> or <u>"<i>hide_completed_tasks_reading</i>"</u>[^3].

## 💭 Property Differences

What is the difference between the "<i>cssclasses</i>" Property of `hide_completed_tasks_reading` and `hide_completed_tasks`?

<details>

<summary><b>hide_completed_tasks_reading</b></summary><br>

This value only hides completed tasks in the <b>"Reading" view</b>, in case you don't want to rely only on the <b>"Source Mode" view</b> to have see and make changes to the completed tasks.

</details>
<details>

<summary><b>hide_completed_tasks</b></summary><br>

By comparison, this value hides completed tasks in both the <b>"Reading" view</b> and  the <b>"Live Preview" view</b>, meaning that you will be able to see and make changes to them only in the <b>"Source Mode" view</b>.

</details>

<b>TL;DR: Comparison table for values, based on Obsidian's view modes:</b>

<table>
    <tr>
        <th>Property / View</th>
        <th>Reading view</th>
        <th>Live Preview</th>
        <th>Source Mode</th>
        <td rowspan="3" valign="top">
            <b>Legend:</b>
            <ul>
                <li>✅: Completed tasks are hidden from this view.</li>
                <li>❎: Completed tasks are not hidden from this view.</li>
            </ul>
        </td>
    </tr>
    <tr>
        <th>hide_completed_tasks_reading</th>
        <td>✅ (Y)</td>
        <td>❎ (N)</td>
        <td>❎ (N)</td>
    </tr>
    <tr>
        <th>hide_completed_tasks</th>
        <td>✅ (Y)</td>
        <td>✅ (Y)</td>
        <td>❎ (N)</td>
    </tr>
</table>

## 🫂 Contributing

Contributions are welcome! While the scope of this repo is quite small, because it's intended to help others out, feel free to:

1. Share improvement ideas via Issues.
2. Create Issues for any potential bug and/or incompatibility.
3. Submit PRs with improvements.
4. Build your own fork, either with improving the .css, or by integrating it into a plugin. (<i>don't forget to leave a credit! it'd make my day. <3</i>)
5. Share your feedback, thoughts and experience!


## 📃 License

This repo is under an MIT license. For more details, you can check the <a href="https://github.com/SharkCee/obsidian-css-hide-completed-tasks/blob/main/LICENSE">LICENSE</a> in the root of this repo.

## 🦈 Support Me

<a href="https://ko-fi.com/sharkcee"><img height="100" alt="Support me on Ko-Fi! (optional!!!)" align="left" src="https://storage.ko-fi.com/cdn/brandasset/v2/support_me_on_kofi_badge_beige.png"/></a>
This repo has not been created for monetizing, with my focus being on sharing helpful resource(s), built on my free time. However, if you wish to support me, you can get me a cuppa on Ko-Fi! This is <b>completely optional</b>, as any type of support makes me happy! ❤️

## 

[^1]: If the entry is not there, either select the 🔄 <b>Reload snippets</b> button, or select the 📂 <b>Open snippets folder</b> button, to make sure that the .css file has been copied correctly (<i>either it hasn't been copied in the `/snippets` folder, or potentially in a different vault's folder</i>).
[^2]: In order to test the newly available entries for the "<i>cssclasses</i>" Property, one or more tasks should be added, so that before and after testing can be performed, and correct functionality can be validated.
[^3]: While applying both values to the "cssclasses" won't lead to errors, you will really only get the same result as using only "<i>hide_completed_tasks</i>", but don't worry, because there's more details in [💭 Property Differences](#-property-differences).
