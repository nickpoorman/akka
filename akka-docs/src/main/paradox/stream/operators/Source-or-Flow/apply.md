# apply

Stream the values of an `immutable.Seq`.

@ref[Source stages](../index.md#source-stages)

@@@ div { .group-scala }
## Signature

@@signature [Source.scala]($akka$/akka-stream/src/main/scala/akka/stream/scaladsl/Source.scala) { #apply }
@@@

## Description

Stream the values of an `immutable.Seq`.

@@@div { .callout }

**emits** the next value of the seq

**completes** when the last element of the seq has been emitted

@@@

