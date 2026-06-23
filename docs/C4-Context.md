@startuml
title C4 Context Diagram - Basic RAG System

actor User

rectangle "RAG Knowledge Assistant" {
}

rectangle "HBR Guide Document" as doc

User --> "RAG Knowledge Assistant"
"RAG Knowledge Assistant" --> doc

@enduml
