# Unreal-Engine-5-GPT-Editor-Utilities

A collection of Unreal Engine 5 Editor Utility widgets powered by GPT3/4.

## Installation

Download and place one of the editor utilities within the UE5 project you wish to use it.

Then make sure to install OpenAI via pip using this method - https://dev.epicgames.com/community/learning/tutorials/lJly/python-install-modules-with-pip-unreal-engine-5-tutorial.  This is the only real requirement but only take a couple of minutes, all editor utilities from this repo should work after step is completed.

**Required pip libraries - openai, sounddevice(if using whisper)**

Open the editor utility in the UE5 editor and place your OpenAI api key in python script blueprint node.

![2023-03-16 10_44_31-CineCamGPT](https://user-images.githubusercontent.com/30479526/225676130-574aeb9a-bd42-4bdc-816d-a36d9d91df8a.png)

## Usage

Right click on on the editor utility and click on "Run Editor Utility Widget".

Double click on the editor utility for full customization through blueprints.

## Information

Each editor utility is made fully in Blueprint with a simple python script node that interacts with GPT3.  Right now this uses the completion method with davinci-003 for the model.  It should be easy to extend / create other utilities using the method, and extend to eventually use GPT4 for a more chat like utility.

## ToDos

- [x] Release first utility
- [ ] Add proper error checking
- [ ] Add more utilities!

We welcome contributions and PRs
