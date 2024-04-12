Mass file update:

```bash
 find -type f -name "VaultConfig.json" | while read file; do
    # Update the file with new content
    echo "$new_content" > "$file"
    echo "Updated $file"
done
```

