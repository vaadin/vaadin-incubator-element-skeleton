[![Available in Vaadin_Directory](https://img.shields.io/vaadin-directory/v/vaadinvaadin-incubator-element.svg)](https://vaadin.com/directory/component/vaadinvaadin-incubator-element)
[![Stars in Vaadin_Directory](https://img.shields.io/vaadin-directory/stars/vaadinvaadin-incubator-element.svg)](https://vaadin.com/directory/component/vaadinvaadin-incubator-element)

# &lt;vaadin-incubator-element&gt;

[&lt;vaadin-incubator-element&gt;](https://vaadin.com/components/vaadin-incubator-element) is a Web Component providing an easy way to ask the user to confirm a choice, part of the [Vaadin components](https://vaadin.com/components).

[<img src="https://raw.githubusercontent.com/vaadin/vaadin-incubator-element/master/screenshot.png" width="200" alt="Screenshot of vaadin-incubator-element">](https://vaadin.com/components/vaadin-incubator-element)

## Example Usage

```html
  <vaadin-incubator-element header="Unsaved changes" confirm-text="Save" on-confirm="save"
    cancel on-cancel="cancel" reject reject-text="Discard" on-reject="discard">
    Do you want to save or discard your changes before navigating away?
  </vaadin-incubator-element>
```
