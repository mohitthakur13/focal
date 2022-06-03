<div class="sidebar">
    <div class="sidebar-element">
        <button class="btn btn-profile">
            <div class="pr-4">
                {@html profileIcon}
            </div>
            <div>{userName}</div>
        </button>
    </div>
    <div class="sidebar-element">
        <button class="btn btn-sidebar-element">Instant</button>
    </div>
    <div class="sidebar-element">
        <button class="btn btn-sidebar-element">Hourly</button>
    </div>
    <div class="sidebar-element">
        <button class="btn btn-sidebar-element">Daily</button>
    </div>
    <div class="sidebar-element">
        <button class="btn btn-sidebar-element">Weekly</button>
    </div>
</div>

<script lang="ts">
    import profileIcon from "./profileIcon";
    let userName = "Simon Baker"
</script>
