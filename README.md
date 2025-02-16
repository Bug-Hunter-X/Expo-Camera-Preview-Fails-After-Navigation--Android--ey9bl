# Expo Camera Preview Rendering Issue on Android

This repository demonstrates a bug where the Expo Camera preview fails to render correctly on Android devices after navigating away from and back to a screen using the camera. The issue is intermittent, appearing more frequently on certain devices or configurations.  The bug and proposed solution are detailed in the corresponding JavaScript files (bug.js and bugSolution.js).

## Setup

1. Clone the repository.
2.  `npm install`
3.  `expo start`

Navigate between screens to reproduce the issue. Note that the problem manifests more often if the screen containing the camera is in a nested navigation stack.