# Decimal

The default counting system, what we humans use on a daily basis. Also known as the base-10 system.

```mdx-code-block
import {
  DiscordInlineCode as Code,
  DiscordCommand as Command,
  DiscordMessages as Discord,
  DiscordMention as Mention,
  DiscordMessage as Message,
} from "@skyra/discord-components-react";

<Discord>
  <Message>399</Message>
  <Message>400</Message>
  <Message>401</Message>
  <Message>402</Message>
  <Message profile="countr" ephemeral>
    <Command slot="reply" command="/count" />
    {"📊 Current count for "}
    <Mention type="channel">counting</Mention>
    {" is "}
    <Code>402</Code>
    {", next up is "}
    <Code>403</Code>
    {"."}
  </Message>
  <Message>403</Message>
</Discord>
```