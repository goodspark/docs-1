---
title: "Workspaces"
icon:
  "<svg viewBox=\"0 0 16 16\" xmlns=\"http://www.w3.org/2000/svg\">\n<path
  d=\"M7.6 0.0984375L0.4 3.49844C0.2 3.59844 0.2 3.89844 0.4 3.99844L7.7
  7.29844C7.9 7.39844 8.2 7.39844 8.4 7.29844L15.6 3.99844C15.8 3.89844 15.8
  3.59844 15.6 3.49844L8.4 0.0984375C8.1 -0.0015625 7.9 -0.0015625 7.6
  0.0984375Z\" />\n<path d=\"M15.6 7.79844L14.1 7.09844C13.9 6.99844 13.6
  6.99844 13.4 7.09844L8.3 9.39844C8.1 9.49844 7.8 9.49844 7.6 9.39844L2.6
  7.09844C2.3 6.99844 2.1 6.99844 1.9 7.09844L0.4 7.79844C0.2 7.89844 0.2
  8.19844 0.4 8.29844L7.7 11.5984C7.9 11.6984 8.2 11.6984 8.4 11.5984L15.7
  8.29844C15.8 8.19844 15.8 7.89844 15.6 7.79844Z\" />\n<path d=\"M15.5984
  12.0984L14.0984 11.3984C13.8984 11.2984 13.5984 11.2984 13.3984
  11.3984L8.29844 13.6984C8.09844 13.7984 7.79844 13.7984 7.59844
  13.6984L2.49844 11.3984C2.29844 11.2984 1.99844 11.2984 1.79844
  11.3984L0.298438 12.0984C0.0984375 12.1984 0.0984375 12.4984 0.298438
  12.5984L7.59844 15.8984C7.79844 15.9984 8.09844 15.9984 8.29844
  15.8984L15.5984 12.5984C15.7984 12.4984 15.7984 12.1984 15.5984 12.0984Z\"
  />\n</svg>"
description: "Learn about development workspaces in Coder."
---

Workspaces contain the dependencies, IDEs, and configuration information needed
for your projects. Coder creates workspaces using a
[shared container image](../images/index.md), which improves their
reproducibility.

![The anatomy of a workspace](../assets/workspaces/workspace-anatomy.png)

## Next steps

Learn how to [create your first workspace](create.md) (see our
[parameter descriptions](workspace-params.md) for additional assistance). Then,
we suggest that you customize your workspace by:

- [Connecting your favorite editors and IDEs](editors.md);
- [Creating dev URLs](devurls.md), which let you access services running in your
  workspace from external machines;
- [Configuring auto-start](autostart.md) so that your workspace is ready when
  you are.
