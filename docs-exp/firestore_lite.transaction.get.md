<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [lite](./firestore_lite.md) &gt; [Transaction](./firestore_lite.transaction.md) &gt; [get](./firestore_lite.transaction.get.md)

## Transaction.get() method

Reads the document referenced by the provided [DocumentReference](./firestore_.documentreference.md)<!-- -->.

<b>Signature:</b>

```typescript
get<T>(documentRef: DocumentReference<T>): Promise<DocumentSnapshot<T>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  documentRef | [DocumentReference](./firestore_lite.documentreference.md)<!-- -->&lt;T&gt; | A reference to the document to be read. |

<b>Returns:</b>

Promise&lt;[DocumentSnapshot](./firestore_lite.documentsnapshot.md)<!-- -->&lt;T&gt;&gt;

A `DocumentSnapshot` with the read data.

