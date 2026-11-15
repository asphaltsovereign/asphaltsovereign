# Source recovery archives

These bundles preserve the source commits from the reviewed engineering workspace before direct browser publication. The project repositories contain the current public working trees. These are source snapshots, not device measurements or newly validated results.

| Snapshot | Recovered commit | SHA-256 |
|---|---|---|
| [octaneos-vehicle-data-intelligence](octaneos-vehicle-data-intelligence.bundle) | `2f1e74e8c4192414f557ec733b9d515f12d02b10` | `4117b90ac1f021122311ba183f9429193145152b07d6b1764a57607559c115ab` |
| [r15v2-powertrain-engineering](r15v2-powertrain-engineering.bundle) | `62bfcf1d3b61b1ede435a4262d9ad86fe49ea4c7` | `d2be710e15bac7294f47e298a1fb56a1d87bc837f0122dc37cee3e846e27802a` |
| [san-v1-automotive-data-acquisition](san-v1-automotive-data-acquisition.bundle) | `1c4c4853c2f7177c97003a76855f851539c5e9fa` | `f1555f9e9d477361b61bf149c3b52affe9376d0ba583d27c247dcfb2983aa15e` |

To inspect a bundle after downloading it:

```bash
git clone --branch main octaneos-vehicle-data-intelligence.bundle recovered-octaneos
```

The archived preparation includes an unexecuted import-workflow experiment. The current project repositories are published using ordinary file commits; no write-enabled import workflow is installed. The portfolio archive is omitted from the current tree because it contains an unpublished CV draft.
