## Description

> [!WARNING]
> ✏️ Please **always** include a summary of the change.
>
> For **feature PRs** explain what new functionality is being introduced (components, styles, logic etc).
> For **bug fixing PRs** describe what issue has been fixed and why it was fixed in the proposed way.
> Please also include any additional relevant motivation or context. List any dependencies that are required for this change.

## Validation Steps

> [!WARNING]
> ✏️ Please include the steps to validate the change. Add relevant pages/screens as well as actions to take.
>
> This is a cross-platform application, that's why before any merge:
> **Make sure to check your PR on three platforms: website, webctv and kepler**. Verify that app is still functional on all of them with your change.

## Screenshots & Videos
<!-- This is optional for most scenarios other than UI changes or frontend, but it is encouraged if there is a tangible way to show your changes. -->

> [!TIP]
> 🚀 Help Speed Up Your PR Approval!
> 💡 Remember, the more you help, the faster you get the green light! 🚦


## Type of change
<!-- 🎯 Must have at least one mark -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Maintenance (documentation, update scripts, update non-major dependencies, etc)
- [ ] Script fix (non-breaking change which fixes a script issue)

## Automation Checklist

- [ ] Create reusable methods and avoid code duplication
- [ ] Create efficient methods which makes code readable
- [ ] Code should be clean and refactor when necessary
- [ ] Don’t Hard code values
- [ ] Avoid unnecessary variables/objects in the memory
- [ ] Avoid sleep & use waits instead.
- [ ] Use CSS/relative xpaths instead of absolute xpaths
- [ ] Page objects should be unique as well as robust
- [ ] Code should be able to accommodate cross-platform compatibility
- [ ] Assertion should be placed separately
- [ ] Test data should come from API
- [ ] Use Step annotation for methods to clearly describe an action

### Testing

## How Has This Been Validated
<!-- Mark the platform that you have tested -->
<!-- 🎯 = required apps -->

### ptv-kepler 🎯
- [ ] Simulator
- [ ] Device

### ptv-website [Desktop] 🎯
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge
- [ ] Other: <!-- ✏️ Please specify your device -->

### ptv-website [Mobile] 🎯
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Other: <!-- ✏️ Please specify your device -->

### ptv-webctv 🎯
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge
- [ ] Device: <!-- ✏️ Please specify your device -->

### ptv-android
- [ ] Simulator
- [ ] Device: <!-- ✏️ Please specify your device -->

### ptv-chromecast
- [ ] Simulator (Web Browser)
- [ ] Device: <!-- ✏️ Please specify your device -->

### Allure Reports
- [ ] I have attached Allure report from atleast 3 platforms or devices
- [ ] I have attached Allure report from atleast 3 platforms or devices
- [ ] I have attached Allure report from atleast 3 platforms or devices
