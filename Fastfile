default_platform(:android)
platform :android do
    lane :uploadToOpenTesting do
        upload_to_play_store(track: "beta",aab:"../build/app/outputs/bundle/release/app-release.aab")
    end
    lane :uploadToClosedTesting do
        upload_to_play_store(track: "alpha",aab:"../build/app/outputs/bundle/release/app-release.aab")
    end
end
