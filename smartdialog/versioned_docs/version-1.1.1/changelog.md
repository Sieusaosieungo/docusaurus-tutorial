---
sidebar_position: 5
---

# Changelog

## 1.3.2 (2021-07-20)

- Move generate script to backend ([#234](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/234))

## 1.3.1 (2021-07-17)

- Upgrade material ui to latest version ([#232](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/232))

## 1.3.0 (2021-07-07)

- Fix bug upload bot picture ([#182](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/182))
- Fix bug change disable field with `send file intent` ([#183](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/183))
- Fix bug entity pagination ([#184](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/184))
- Fix bug action mapping cache state ([#185](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/185))
- Fix bug warning when refresh new script page ([#188](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/188))
- Refactor history ([#187](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/187), [#228](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/228))
- Add origin intent ([#193](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/193))
- Fix bug turn on action mapping without choose any action ([#195](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/195))
- Add feature export, import intent ([#223](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/223), [#224](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/224))
- Add QC Report ([#228](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/228))
- Add DIET NET model ([#229](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/229))
- Fix training tab ([#230](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/230))

## 1.2.9 (2021-06-02)

- Change favicon and brand name ([#225](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/225)).

## 1.2.8 (2021-05-21)

- Add addition configuration for chatbot ([#221](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/221)).

## 1.2.7 (2021-05-21)

- Add asr breaking time default ([#216](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/216)).
- Split expected data type to asr and bot ([#217](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/217), [#218](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/218), [#219](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/219)).

## 1.2.6 (2021-05-14)

- Remapping expected data type number ([#211](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/211)).
- Fix missing focus asr breaking time input ([#214](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/214)).

## 1.2.5 (2021-05-13)

- Add `asr_provider` ([#205](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/205)).
- Add `asr_breaking_time` ([#208](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/208)).

## 1.2.4 (2021-04-02)

- Change upload url for image action card ([#203](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/203)).

## 1.2.3 (2021-03-27)

- Update mapping expected data type ([#201](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/201)).

## 1.2.2 (2021-03-24)

- Add asr type identity_card ([#199](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/199)).

## 1.2.1 (2021-03-20)

- Fix auth admin page ([#178](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/178)).
- Add more expected data type ([#196](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/196)).

## 1.2.0 (2021-02-21)

- Fix auto convert api response in json api card ([#173](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/173)).
- Add user say source ([#175](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/175)).
- Add params to connect agent card ([#174](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/174)).
- Add face mask in action card ([#171](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/171)).
- Add entity context ([#163](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/163)).
- Add required params ([#164](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/164)).

## 1.1.0 (2021-01-12)

- Hide auto save workflow ([#162](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/162)).
- Fix bug update usersay status created new usersay ([#165](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/165)).
- Add action card `FORWARD_TO_AGENT` ([#166](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/166)).
- Add import overwrite and append intent ([#152](https://github.com/DevStorevn/vbee_smartdialog_frontend/pull/152)).

## 1.0.0 (2020-12-04)

### Functionality

- Overview

  - Statistic: Bot Efficiency, Working data.

- Entities

  - Group entities.
  - Define synonyms entity with Combine all values, Synonym only and Get exact value options.
  - Regex entity.
  - Complex entity with Combine all values and Get exact value options.
  - Hashtag.

- Intents

  - Group intents.
  - Import intents.
  - Context.
  - Usersay.
  - Parameters.
  - Action mapping.
  - Inform intent.
  - Send file intent.
  - Disable intent.
  - Hashtag.

- Usersay Template

  - Group usersay templates.
  - Parameters.

- Actions

  - Group actions.
  - Import actions.
  - Action cards.
  - Hashtag.

- Dictionary

  - Acronym.
  - Original word.

- Workflows

  - Group workflows.
  - Create workflow by drawing a flow.

- Scripts

  - Group scripts.
  - Create script by chatting.

- Workflow templates

  - Group workflow templates.
  - Create workflow template by drawing a flow.
  - Replace or attach to Workflow.

- History

  - List conversations.
  - Search conversation.
  - Convert conversation to Script.

- Testing

  - Testing models: Intent model, Entity model, Action model.
  - Testing methods: Split training data, Excel file.

- Training

  - Intent model.
  - Entity model.
  - Action model.

- Versions

  - Detail information of Intent, Entity, Action models.

- Reports

  - Preview report according to customized information.
  - Export report as Excel/PDF/CSV files.

- Management

  - Manage according to the data group.

- Settings

  - General settings.
  - Version settings.
  - Export and Import.
  - Model.
  - Clone template package.
  - Share bot.
  - Delete bot.
