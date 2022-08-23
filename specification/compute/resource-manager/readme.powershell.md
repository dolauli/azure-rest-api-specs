## PowerShell

### Tag: CloudService

These settings apply only when `--tag=CloudService` is specified on the command line.

```yaml $(tag) == 'CloudService'
input-file:
  - Microsoft.Compute/CloudserviceRP/stable/2021-03-01/cloudService.json
```
### Tag: Compute

These settings apply only when `--tag=Compute` is specified on the command line.

```yaml $(tag) == 'Compute'
input-file:
  - Microsoft.Compute/GalleryRP/stable/2022-01-03/gallery.json
  - Microsoft.Compute/ComputeRP/stable/2021-07-01/runCommands.json
```