# Synapse Layer

Persistent zero-knowledge memory for AI agents. Store, recall and transfer encrypted context across models.

## Commands

### remember
Store a memory with zero-knowledge encryption.
```bash
synapse remember "User prefers concise responses" --user user_123 --importance 0.8
```

### recall
Recall memories using semantic search.
```bash
synapse recall "communication preferences" --user user_123 --limit 5
```

### handover
Transfer context to another model.
```bash
synapse handover --to gpt --user user_123 --expires 3600
```

### import
Import memory blob.
```bash
synapse import --blob <base64> --user user_123
```

### status
Check vault health.
```bash
synapse status --user user_123
```

### forget
Delete memories.
```bash
synapse forget "old preferences" --user user_123
```

## Installation

```bash
npx synapse-layer remember "text" --user user_123
```

## MCP Server

https://rbeycxzizrrdmxpilepc.supabase.co/functions/v1/mcp-server

## Keywords

agent persistent memory, cross-model context transfer, zero-knowledge memory, recall past conversation, memory handover, MCP memory tool, neural handover, conflict resolution memory, semantic memory search, agent state persistence
