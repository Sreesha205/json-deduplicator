# JSON Deduplicator

This Python command line application efficiently de-duplicates a set of JSON records based on specific rules, ensuring that each record's ID and email are unique. It prioritizes newer data and handles records with identical timestamps by preferring the last provided record in the list.

## Project Description

The JSON Deduplicator reads a variable number of identically structured JSON records and reconciles duplicates by:
1. Preferring data from the most recent date.
2. Ensuring unique IDs and email addresses.
3. Preferring the last record if dates are identical.

The application also logs changes, detailing field modifications between source and output records.

## Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/Sreesha205/json-deduplicator
cd json-deduplicator
pip install -r requirements.txt
