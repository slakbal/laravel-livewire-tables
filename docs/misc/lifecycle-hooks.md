---
title: Lifecycle Hooks
weight: 7
---

With the migration to Livewire 3, there we are implementing several Lifecycle Hooks to assist with re-using methods across multiple Table Components.

## configuring
This is called immediately prior to the configure() method being called

## configured
This is called immediately after the configure() method is called

## settingColumns
This is called prior to setting up the available Columns via the columns() method

## columnsSet
This is called immediately after the Columns are set up
