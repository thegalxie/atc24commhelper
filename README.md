# Comm Helper for ATC24 Frequency changes

This is a self-contained static website ready for GitHub and Vercel. It has no dependencies and no build command.

## Deploy with GitHub and Vercel

1. Create a new GitHub repository and upload the contents of this folder to the repository root.
2. In Vercel, select **Add New → Project**, then import that GitHub repository.
3. Leave the framework preset as **Other**. Do not set a build command or output directory.
4. Select **Deploy**.

Vercel serves `index.html` from the repository root. `vercel.json` keeps the frequency CSV uncached so a newly deployed frequency list is read on the next page load.

## Updating the frequency list

Edit `frequencies.csv`, using one record per row:

```csv
24850,IRCC,discord://discord.com/channels/919656909563371600/1409259489580023898
```

The columns are: five digits after the implied leading `1`, identifier, and Discord app link. Commit and push the edited CSV to GitHub; Vercel will deploy the change automatically.
