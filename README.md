# GraspAI-Landing-Page

## Installation of Hugo
https://gohugo.io/installation/
Follow the steps for your OS and install the extended version.

## Directories
- Infos about it can be found here: https://gohugo.io/getting-started/directory-structure/#directories

## Running the Hugo Server
```sh
hugo server [-D]
```
The -D flag includes the draft content in the build, so some draft files.
Read more about it here: https://gohugo.io/getting-started/usage/#draft-future-and-expired-content

## Deploy
Only on main branch
- this will cause an action workflow to run to generate the site for github pages. No need to run the build locally.

## Building the Hugo Project (Local)
```sh
hugo [flags]
```
