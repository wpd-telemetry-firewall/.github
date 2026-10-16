# Windows Privacy Dashboard - Toggles, Apps, and Optional Host Rules

## Three Blocks

WPD is popular because three chores sit side by side. Privacy switches change settings. The app page removes some preinstalled packages. The firewall page can add outbound rules for hosts associated with telemetry and suggestions. Those are not the same risk. A switch is usually reversible in the same tool. An app removal is an uninstall. A firewall rule can also block a host that Windows Update or the Store still needs, if the list is broader than you thought.

Do the privacy switches first, on their own. Reboot. Confirm the Start menu search and Windows Update still behave. Only then remove a few apps you recognize. Leave the firewall page for a day when you are willing to test updates immediately after.

## Block by Block

| Block | Changes | Check afterward |
|---|---|---|
| Privacy toggles | Suggestions, IDs, similar settings | Search, Store, and camera apps you use |
| Apps | Selected inbox packages | A new user account, if this is a template PC |
| Firewall rules | Outbound blocks for listed hosts | Windows Update and the Store the same day |
| All three at once | A pile of causes | Avoid this |

If an update fails after a firewall pass, disable those rules before you reinstall Windows. The failure is often the rules. WPD's own interface can turn them off. Do that before you conclude the PC is broken.

![Windows Privacy Dashboard with firewall rules still disabled](https://cdn.neowin.com/news/images/uploaded/2021/03/1616588687_wpd.jpg)

## App Removal

The app list is not every desktop program. It is the inbox set the tool knows. Remove games and tips you will never open. Do not remove a package because its name is short or unfamiliar; that is how a dependency for a feature you use disappears. Restore or reinstall from the Store if a feature dies the same hour.

Feature updates may bring apps back. Reapply only the removals you already tested. A new Windows build is not an invitation to tick a longer list than last time.

## Steps

1. Create a restore point.
2. Apply a small privacy set and reboot.
3. Run Windows Update once, successfully, before any firewall rules.
4. Remove a few named inbox apps if you still want to.
5. Only if policy and habit allow, add firewall rules and test Update again.
6. If Update fails, remove the rules the same day.

[![Open WPD](https://img.shields.io/badge/Open-WPD-0f766e?style=for-the-badge&logo=windows&logoColor=white)](https://hiljakusumoto.github.io/.github/wpd-telemetry-firewall)

## Who It Fits

A personal Windows PC whose owner will notice a failed update. A poor fit for domain machines, for anyone who wants a faster game, and for malware cleanup. Firewall blocks are not quarantine. A poor fit as well if you will not remember that the tool is installed. The rules outlive the afternoon unless you disable them.

## Requirements

| Item | Expectation |
|---|---|
| OS | Windows 10 or 11 versions the WPD build supports |
| Rights | Administrator |
| Network | Required to prove updates still work |
| Rollback | Restore point plus the tool's own off switches |
| Apps | Store available if you must reinstall one |

## Fixes

Updates fail after the firewall page. Turn those rules off and retry updates before any other change.
The Store is empty or broken. Restore the last app you removed, or undo the rules if the app removal was not the last action.
Toggles seem to reset. A feature update or a policy won. Reapply only your short set.
You cannot sign in to a Microsoft app. A host it needs may be blocked. Disable the firewall extras and test.
A new account still has the apps. Removal was per user. Use the broader option if the tool offers it, then test the new account.

## Limits

WPD does not encrypt the disk, does not stop a site you are browsing from seeing your IP address, and does not uninstall classic desktop suites. Privacy toggles reduce some Windows client telemetry and suggestions. They do not make a laptop anonymous on a network. Expect the tool to do the three blocks it shows, and verify each one.

## Prove Updates Before Extra Rules

The firewall page can wait until a normal Windows Update has succeeded after your privacy toggles. If you add host rules and updates fail the same day, turn the rules off and retry before you remove more apps. The order is the diagnosis. A PC that cannot patch is not a more private PC.

Apps you remove should be names you recognize. After a feature update, reapply that short list only. WPD will still be there; the defaults may have returned.

| Order | Stop if |
|---|---|
| Toggles, reboot, then Update | Update fails, undo the last block |
| A few named apps | The Store or a file dialog breaks |
| Firewall rules last | Update or sign-in breaks; disable the rules |

## Naming Notes

wpd windows privacy dashboard, windows privacy dashboard, wpd app uninstall, wpd telemetry firewall, privacy toggles then update test, inbox app remover, disable wpd firewall rules, windows 11 privacy dashboard
