# Changelog - Home-Assistant-Matter-Hub (Alpha)

⚠️ **WARNING: This is an alpha version for testing purposes only!**

This addon contains pre-release features that may be unstable or incomplete.
Use at your own risk and please report any issues on GitHub.

---

## [1.4.0-alpha.1] - Initial Alpha Release

### New Features
- **Health Check API** (`/api/health`) with uptime, status, and service info
- **Kubernetes-ready probes** (`/api/health/live`, `/api/health/ready`)
- **WebSocket live updates** (`/api/ws`) for real-time bridge status
- **Entity Mapping Customization**:
  - Override Matter device types per entity
  - Custom names for entities
  - Disable entities from bridge

### Technical Changes
- Node.js 24 (LTS)
- Dropped armv7 support (only amd64 + arm64)
