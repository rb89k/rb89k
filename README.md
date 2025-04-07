## Documentation and retrospectives 👋

<!-- TO-DO 
- Upload webrtc directory and test cases.
-->

### 🔭 I’m currently working on ...  

- Peer-to-peer WebRTC application https://github.com/rb89k/p2pwebrtc/tree/main  
- using an ESCPOS receipt printer to output reminders, notes, tasks, etc. using the socat utility tool.

### Recent updates

- 🎉 Successfully received IDE approval.

While working with software engineers on a large, complex project in a highly regulated field, we pinpointed inter-component communication via messaging as a significant risk. The application's non-determinism, caused by timing variations and complexity, made comprehensive test automation difficult for these interactions. Therefore, we strategically focused manual testing efforts on validating the functionality of these high-risk communication pathways.

### Bug Reporting

<details>
  <summary>Checklist</summary>
  
  - [ ] Provide a description of issue or defect observed.
  - [ ] State the expected behavior.
  - [ ] State the actual behavior.
  - [ ] List the reporter (i.e. person who observed the issue).
  - [ ] State the test environment.
    - [ ] List the software version.
    - [ ]  Include configuration settings (e.g. workstation, virtual machine, operating system)
    - [ ]  Include the log/data path location (e.g. cloud storage/file directory).
    - [ ]  Provide supporting evidence indicated the stated behavior (screenshots, timestaps, logs).
  - [ ]  List detailed steps to reproduce the issue.  

![defect-report-flowchart](https://github.com/user-attachments/assets/e9348473-498b-431e-a14f-829d60869df1)
</details>


### Pull Request / Development Testing

<details>
  <summary>Checklist</summary>
  
#### Describe Your Changes
<!-- State your reason for change. -->
Add description of changes

#### Ticket Link
<!-- Connect Jira API Key, then the ticket number and GitHub will auto-link to Jira. -->
Add Jira API key

#### Type of change
<!-- Select an option according to the type of change. -->

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Release
- [ ] Non-code change

#### Development PR Checklist (Main Branch)
<!-- Delete this section if this is not a development PR -->

- [ ] Changes are tested
- [ ] Relevant documentation is updated

#### Release PR Checklist (Release Branch)
<!-- Delete this section if this is not a release PR -->

- [ ] Release number identified: vX.Y.Z
- [ ] Relevant PRs listed in description above
- [ ] Impacted components identified:
    - List impacted components 
- [ ] System tests requested
    - Tester: 
    - Test Confluence Page: 
- [ ] System tests passed (tester should approve this PR)
- [ ] *replace with DEV/QA Lead's approval (or delegate) obtained

</details>

#### Test Planning for Event-Driven Design

The approach to the pub-sub communication model was largely based on risk assessment with a focus on manual testing at the functional level 
due to the non-deterministic nature of the application. Efforts to automate tedious tasks such as verifying success/exit criterions occurred at the unit 
and integration level within the CI/CD pipeline. 

<details>
  <summary>Pub-Sub Model</summary>

##### Sequence Diagram

![pub-sub-model](https://github.com/user-attachments/assets/d34f307f-4f8c-4f2b-8bf4-c4f15987c54e)

</details>

-------------------------------------------------------------------------------------------------------

<details>
  <summary>Happy Path Workflow</summary>

##### Flowchart Diagram

![happy-path-workflow](https://github.com/user-attachments/assets/e8c40b08-ffdb-4024-a576-298ce89b230c)

</details>

-------------------------------------------------------------------------------------------------------

<details>
  <summary>Test Suite 1 Example</summary>

##### YAML File Validation Example

![module1-example](https://github.com/user-attachments/assets/3cc35d2f-d4bf-464c-b9c5-686db2bfad37)


![module-steps](https://github.com/user-attachments/assets/b7c1f25c-4d20-42b7-ae63-89619b77d777)

</details>

-------------------------------------------------------------------------------------------------------


