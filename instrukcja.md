---
title: Tutorial
---


## The ClusterRoleBinding creation and binding the testee_initials_recruitment group to the kyma-edit ClusterRole

## Prerequisites

> The action described in the tutorial requires an access to the website: <a href="https://console.tw-task.wookiee.shoot.canary.k8s-hana.ondemand.com">https://console.tw-task.wookiee.shoot.canary.k8s-hana.ondemand.com/</a>  with the credentials provided by the Software Development Manager.

## Step 1

Click the "Administration" button on the menu on the left side of the website, then choose an option "Global Permissions".

## Step 2

Choose the option "+ Create Binding", which is above the list of Cluster Role Bindings (on the right side).

## Step 3

In the pop-up window, there is a need to check the option "User group", name the user group in the following pattern "your_initials_recruitment" and choose the role "kyma-edit".

## Step 4

Click the "Save" button.
