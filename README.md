version: 2
updates:
  - package-ecosystem: "github-actions"
    directory: "/"
    schedule:
      interval: "weekly"
    open-pull-requests-limit: 10
    labels:
      - "area/ci"
      - "dependencies"

  - package-ecosystem: "docker"
    directory: "/packaging/docker"
    schedule:
      interval: "weekly"
    open-pull-requests-limit: 5
    labels:
      - "area/docker"
      - "dependencies"