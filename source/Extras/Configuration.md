# Available Configuration Keys

## In Constants.xaml:
- `UseThemeExtras` (Boolean) - Enable/disable all Extras features
- `EnableBannerCache` (Boolean) - Cache banner images locally
- `EnableVideoMetadata` (Boolean) - Support video metadata
- `ExtrasMetadataPath` (String) - Path to metadata directory

## Usage in XAML:
```xml
Tag="{DynamicResource UseThemeExtras}"
Tag="{DynamicResource EnableBannerCache}"


---

### **Summary of Changes**

| File | Change Type | Key Addition |
|------|------------|--------------|
| Constants.xaml | Modified | Theme Extras configuration keys |
| GlobalResources.xaml | Modified | Extras converters and namespaces |
| App.xaml | Modified | Extras resource dictionaries |
| Main.xaml | Modified | Banner display support |
| GameDetails.xaml | Modified | Custom metadata section |
| Extras/Theme.xaml | Created | Extras styling |
| Extras/Controls/CustomControls.xaml | Created | Custom control templates |
| LocSource.xaml | Modified | Localization strings |

---

### **Next Steps**

1. **Start with Phase 3-5**: Update configuration and resources
2. **Test each view file** after modification (Phases 6-7)
3. **Create Extras subdirectory files** (Phase 8)
4. **Verify in Playnite** with each theme setting toggle
5. **Document any conflicts** or custom adjustments needed

This approach allows gradual integration with testing at each step!
