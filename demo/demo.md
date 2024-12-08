# Visual Studio Code with GitHub Copilot Demonstration Script

This script demonstrates the capabilities of GitHub Copilot in Visual Studio Code.

## October 2024 (version 1.95)

- [October 2024 (version 1.95)](https://code.visualstudio.com/updates/v1_95)

### [Copilot Edits](https://code.visualstudio.com/updates/v1_95#_start-a-code-editing-session-with-copilot-edits)

1. Open `Copilot Edits`

![Image](https://github.com/user-attachments/assets/381f9e16-7e09-4da3-bfe8-3090aba8e338)

2. Add Owner related classes

Add the following files to working set:

- `Owner.java`
- `OwnerController.java`
- `OwnerRepository.java`

3. Input the following prompt:

```text
I want to add a attribute to Owner class which is Age. And I want to add APIs and their endpoints to operate Owner class with age as a key.
```

<details><summary>Prompt sample</summary>
<img src="https://github.com/user-attachments/assets/9b7faed3-3caf-4b23-989d-b7611cfea18b">
</details>

<details><summary>Copilot Answer sample</summary>
<video src="https://github.com/user-attachments/assets/07cdde99-167d-40d2-8189-12a9451a85ff" controls="true"></video>
</details>

### [Copilot Chat in Secondary Side Bar](https://code.visualstudio.com/updates/v1_95#_chat-in-the-secondary-side-bar)

Originally you can found the GitHub Copilot Chat view in the primary side bar. Now you can see it in the secondary side bar as a default.

![Image](https://github.com/user-attachments/assets/acdea5ea-b8cb-4945-a0d3-1d097ff60010)

#### Command Center

In the case of Command Center:

![Image](https://github.com/user-attachments/assets/030847a6-6d56-4f69-bdf4-062e3cf3cb81)

👇

![Image](https://github.com/user-attachments/assets/39541db2-4cd5-4dc5-95b2-3d1c82580acf)

👇

![Image](https://github.com/user-attachments/assets/5522eb77-2d67-44e4-a1e9-d00be46fd7d5)

#### Keyboard Shortcuts

In the case of Keyboard Shortcuts:

- `Ctrl` + `Alt` + `I` to open the Copilot Chat

### [Copilot code reviews](https://code.visualstudio.com/updates/v1_95#_copilot-code-reviews)

You can delegate code reviews to GitHub Copilot to review changes, rather than human reviewers.

- There are two ways to use Copilot code review in VS Code:
  - Review selection
    - Select the code you want to review
     `Copilot` > `Review and Comment` from the **Editor Context Menu**
    - `GitHub Copilot: Review and Comment` command from the **Command Palette**
  - Review Changes
    - Select the `Copilot Code Review button` in the **Source Control view**

1. Open `Copilot Edits`

2. Add Owner related classes

Add the following files to working set:

- `Owner.java`
- `OwnerController.java`
- `OwnerRepository.java`

3. Input the following prompt:

```text
I want to add a attribute to Owner class which is Age. And I want to add APIs and their endpoints to operate Owner class with age as a key.
```

4. Accept the Copilot suggestion

5. Select Source Control view

6. Select the `Copilot Code Review` button

![Image](https://github.com/user-attachments/assets/e15481de-d09c-4a77-987a-caa41e27ceff)

👇

![Image](https://github.com/user-attachments/assets/7e07cc5e-18a2-4521-be93-db7156ae0894)

### [Automatic chat participant detection](https://code.visualstudio.com/updates/v1_95#_automatic-chat-participant-detection)

You might have seen chat participants in the Copilot Chat, like following:

![Image](https://github.com/user-attachments/assets/acc246cb-e65c-4dff-95af-0a6c91197e27)

Originally, `Chat Participant` had to explicitly specify which one to add, but now the context is interpreted and chat participant is automatically added as needed.

1. Open `Copilot Chat`

2. Input the following prompt:

```text
How does this Spring boot application accept user requests and resond to them?
```
<details><summary>Copilot Answer sample</summary>
<img src="https://github.com/user-attachments/assets/a7160f1e-dfe5-446b-83fe-56af0d627334">
</details>

### [Control current editor context](https://code.visualstudio.com/updates/v1_95#_control-current-editor-context)

Copilot Chat has always included the currenlty opened file or your currenlt selection. But sometimes, when you ask a question that is not about your current editor, including this context might affect how the model interprets your question.

You can hide your current visible file with ![Image](https://github.com/user-attachments/assets/f886428c-e611-4e2a-8240-9e8cdfca33b6)

![Image](https://github.com/user-attachments/assets/74a72649-4923-4941-9ba7-769c8550147b)
![Image](https://github.com/user-attachments/assets/ff8c2f7a-d147-485f-a8fe-29f3bd646e0b)
![Image](https://github.com/user-attachments/assets/9352d62d-97de-446e-978a-9f89f37be798)

### [Interactive workspace symbol links](https://code.visualstudio.com/updates/v1_95#_interactive-workspace-symbol-links)

### [Fix using Copilot action in the Problem hover](https://code.visualstudio.com/updates/v1_95#_fix-using-copilot-action-in-the-problem-hover)

### [Workspace indexing](https://code.visualstudio.com/updates/v1_95#_workspace-indexing)

### [Sort by relevance in Semantic Search (Experimental)](https://code.visualstudio.com/updates/v1_95#_sort-by-relevance-in-semantic-search-experimental)

### [Copilot extensibility](https://code.visualstudio.com/updates/v1_95#_copilot-extensions-showcase)
